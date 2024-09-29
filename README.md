# GUI

## streamlit

- thực hiện nhập đầu vào từ người dùng, thực hiện kết nối đến agents thông qua socket
- Dữ liệu được gửi đi
```python

{
  'user' : '<username>',
  'content' : [
      {
          'role' : 'user',
          'content' : [
              {
                  'text' : 'Nội dung tin nhắn'
              }
          ]
      },
      {
          'role' : 'assistant',
          'content' : [
              {
                  'text' : 'Nội dung tin nhắn'
              }
          ]
      },
      ...
  ]
}

```

## other

# AGENTS
