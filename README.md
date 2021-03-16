# git-practice
このリポジトリはGit動画講座用です．
ローカルリポで変更　　
conflictブランチで変更(コンフリクト発生)
conflit-remote上で更新(コンフリクト発生)
stash練習(1st)

md 練習
```python
class MyClass():
  def __init__(self):
    x = 0
	y = x
    pass
	
  def print_string(self, s):
    print(s)
```

```c++
#include <stdio.h>
#include "mysrc.h"

#define MAX 1000

class MyClass{
  private:
	int x;
  public:
	char s[100];
	void print(char s){
		printf("%s\n", s);
	};
};

int main(void){
  int x = 0;
  char s[100];

  scanf("%d", &x);
  printf("%d", x);
  printf("%s", s);
};
