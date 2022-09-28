## react netlify blank screen

Message: 
Failed to load resource: the server responded with a status of 404 ()





1. 這個關掉
https://dev.to/kapi1/solved-treating-warnings-as-errors-because-of-process-env-ci-true-bk5

2. package.json 這行拿掉：
https://answers.netlify.com/t/react-app-is-just-a-blank-page-on-live-site-works-perfectly-on-localhost/54071/4

"homepage": "https://sunpochin.github.io/react-memory-card-pokemon",
它存在是因為原本用 github page, 可是 netlify 一 push 就開始 build 感覺比較快，所以我想都換成 netlify.
 