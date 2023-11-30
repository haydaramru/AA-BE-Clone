Relative Path:
Instead of using an absolute import path like "db/users", try using a relative path that reflects the file structure. For example:

```typescript
import { UserModel } from "../db/users"; // Adjust the path accordingly
```

```bash
git commit . -m "refactor: change import absolute path into relative path"
```