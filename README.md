# GraphQL Demo

### From the talk

**GraphQL For The Rest Of Us:** 
_New Things for People Who Work On Old Things_

## Getting Started

**_Install Dependencies_**
```bash
npm install
```

**_Run the Mock Data API (Terminal Window 1)_**
```bash
npm run start:api-server,
```

**_Run the GraphQL API (Terminal Window 2)_**
```bash
npm run start:graphql-server
```

**_Navigate to http://localhost:5000_**

## Sample Query

```
{
  posts(page: "2") {
    title
    author {
      lastName
      company {
        companyDescription
      }
    }
  }
}
```

---

## License

MIT
