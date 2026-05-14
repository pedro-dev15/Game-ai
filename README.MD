game-ai/
│
├── frontend/ # Frontend Next.js/React
│ │
│ ├── src/
│ │ ├── app/
│ │ ├── components/
│ │ ├── services/
│ │ ├── hooks/
│ │ ├── contexts/
│ │ ├── styles/
│ │ └── utils/
│ │
│ ├── public/
│ │
│ └── package.json
│
│
├── backend/ # Backend principal NestJS
│ │
│ ├── src/
│ │ │
│ │ ├── auth/
│ │ ├── users/
│ │ ├── chat/
│ │ ├── games/
│ │ ├── ai/
│ │ ├── common/
│ │ └── main.ts
│ │
│ ├── prisma/
│ │ ├── schema.prisma
│ │ └── migrations/
│ │
│ └── package.json
│
│
├── ai-service/ # Serviço Python IA/RAG
│ │
│ ├── rag/
│ ├── scraping/
│ ├── embeddings/
│ ├── prompts/
│ ├── vector_db/
│ │
│ ├── main.py
│ │
│ ├── requirements.txt
│ └── Dockerfile
│
│
├── infrastructure/
│ │
│ ├── nginx/
│ ├── docker/
│ └── scripts/
│
│
├── .env
├── docker-compose.yml
├── .gitignore
└── README.md
