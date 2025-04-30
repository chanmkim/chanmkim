# B2B Chat Application

## 프로젝트 소개

B2B Chat은 기업 간 커뮤니케이션을 위한 CS챗봇. Next.js 13 App Router와 Supabase를 활용하여 구축되었음

🔗 **Live Demo**: [https://b2b-chat.vercel.app/](https://b2b-chat.vercel.app/)

## 기술 스택

- **Frontend**: Next.js 13 (App Router), React, TypeScript
- **Styling**: Tailwind CSS, shadcn/ui
- **Backend**: Supabase
- **상태 관리**: TanStack Query, Zustand
- **폼 관리**: React Hook Form, Zod
- **유틸리티**: date-fns, ts-pattern

## URL 구조

```
/ - 메인 페이지
├── /auth
│   ├── /signin - 로그인
│   └── /signup - 회원가입
├── /dashboard
│   ├── /chat - 채팅 목록
│   ├── /profile - 프로필 관리
│   └── /settings - 설정
└── /company
    ├── /[id] - 기업 상세 정보
    └── /manage - 기업 관리
```

![image](https://github.com/user-attachments/assets/502c37e5-4ea0-4e37-b826-adf5c307ec70)



