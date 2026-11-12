## Mermaid テスト０１

```mermaid
graph TD;
    A[スタート] --> B[学習開始];
    B --> C{学習意欲はあるか};
    C -- Yes --> D[たぶん成功];
    C -- No --> E[人生損するよ];
    D --> F[終了];
    E --> F;


```