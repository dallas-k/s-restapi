# s-restapi
## studying rest api with python

1. Python을 설치한다
2. API를 호출하기 위해 request 모듈을 설치한다. `pip install requests`


## REST API란?
> API를 일정한 규칙을 가지고 설계하고, 호출하기 위해서 만들어진 규칙.
> * Headers : 해당 API의 메타 데이터를 담고 있다. ex. "Content-Type" : "application/json"
> * Get의 Params : 쿼리스트링 값인 `?key=value`의 내용을 담고 있다. Python으로 호출 시 `requests.get(url, params="  ")` <br/> 
> 
> * Post의 Body : 요청문의 data 값을 담고 있다
> * Python 호출 예시
> * HTML양식 : `requests.post(url, data="   "`
> * JSON양식 : `requests.post(url, json="   "`
