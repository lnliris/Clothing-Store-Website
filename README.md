# Clothing Store (FE + BE)

This is a monorepo for the Clothing Store application:
- `fe/`: Frontend (React + Ant Design)
- `be/`: Backend (Spring Boot + MongoDB Atlas + VNPay)

## Repository structure

```text
.
├─ fe/   # Web client
└─ be/   # REST API / business logic
```

## Quick start

### 1) Frontend (`fe/`)

1. Open a terminal in `fe/`
2. Install dependencies:

```bash
cd fe
npm install
```

3. Start the development server:

```bash
npm run dev
```

### 2) Backend (`be/`)

1. Open a terminal in `be/`
2. Run with Gradle:

```bash
cd be
./gradlew bootRun
```

## More documentation

See:
- `fe/README.md`
- `be/README.md`
