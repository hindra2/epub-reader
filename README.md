To build for development:

```bash
1. cd epub-reader
2. npm install
3. eas build --profile=development
4. npm run start
```

To create a build to share with others:

```bash
1. cd epub-reader
2. npm install
3. eas build --profile=preview
```

To add additional ios users:

```bash
eas device:create
```

To create a GitHub repository for this project, run:

```bash
npx rn-new --publish
```
