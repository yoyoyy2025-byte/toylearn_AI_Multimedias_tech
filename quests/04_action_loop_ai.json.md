``` 
prompt
너는 정리를 굉장히 잘하는 천재야
입력 값 중 content 필드 값을 간단하게 줄여줘
입력값에 맞춰서 작성 반드시 뉴스형식으로 작성해야해 


## 입력값

{



"title": {{ $json.title }},

"link": {{ $json.link }},

"content": {{ $json.content }}

"pubDate": {{ $json.pubDate }}


}