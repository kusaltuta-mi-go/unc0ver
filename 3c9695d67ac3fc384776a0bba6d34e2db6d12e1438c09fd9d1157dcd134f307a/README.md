# 🥺 morethan-log

<img width="1314" alt="image" src="https://user-images.githubusercontent.com/72514247/177747208-cc01cc79-e9af-4009-be70-f2182bde5c4e.png">

노션을 활용한 개인 블로그 입니다. 이제 더 이상 게시글 작성을 위해 커밋을 할 필요가 없습니다. 노션을 이용하여 게시글을 작성하고, 블로그를 통해 내용을 공유해보세요!

## Features

### 📒 notion을 이용한 게시글 작성

- notion에 글을 작성하면 즉시 블로그에 반영됩니다.
- 글 작성을 위해 별도의 배포이후 커밋을 할 필요가 없습니다.

### 👀 SEO 지원

- 게시글에 대해 동적으로 OG IMAGE(썸네일!)를 생성합니다.
  - og-image에서 한글이 적용이 안되는 오류를 수정하여 적용했습니다. [og-image-korean](https://github.com/morethanmin/og-image-korean)
- 게시글에 대해 동적으로 sitemap을 작성합니다.
  - 기존의 배포시 적용되는 방식에서 동적으로 적용되도록 수정하여 적용했습니다.

### 🤖 CONFIG를 통한 다양한 Plugin 지원

- 본인의 프로필 정보를 쉽게 세팅할 수 있습니다.
- GA, utterances를 쉽게 연동이 가능합니다.
- 댓글 기능이 지원됩니다.

### 📄 Page 생성 기능

- 게시글 작성 이외에 노션 페이지를 보여줄 수 있는 기능을 추가하였습니다. 
- 노션으로 만들어진 이력서, 포트폴리오 등을 공유할 때 유용하게 사용이 가능합니다.

## Quick Start

- 해당 저장소를 fork 해주세요.
- Customize `blog.config.js`을 본인에게 맞도록 수정해주세요.
  - notion config의 pageId는 본인의 notion에 [해당 페이지](https://quasar-season-ed5.notion.site/12c38b5f459d4eb9a759f92fba6cea36?v=2e7962408e3842b2a1a801bf3546edda)를 복제해주세요. 
  - 공유 > 웹에서 공유를 켜주시면 url이 나오는데, www.notion.so/[pageId]?v=[version] 에서 pageId를 입력해주시면 됩니다.
- [Vercel](https://vercel.com/dashboard)을 사용하여 배포를 해주세요.
  - 해당 repo를 선택하고 별다른 설정없이 바로 배포가 가능합니다!

## Tech Stack

- Next.js
- tailwind
- notion-client

## License

The MIT License.

> This projects is based on [nobelium](https://github.com/craigary/nobelium).
