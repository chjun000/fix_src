# fix_src

[board 소스 수정 내역]

1. PolicyHandler.java
  - 마지막에 } 괄호 누락 되어있었어요. 올려주시기 전에 수정하시면서 빼먹으신듯..^^

2. AbstractEvent.java
  - public boolean isMe(){
        return getEventType().equals(getClass().getSimpleName());
    }
  - 이 부분이 빠져 있어서 다른 소스랑 동일하게 넣었습니다~
