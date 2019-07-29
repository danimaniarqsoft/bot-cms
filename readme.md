
```
npm install
```
Create an .env file from .env_sample and change the variables
```
cp .env_sample .env
```
```
PLATFORM=web
TOKENS=youwillneverguessmysecretbottoken
USERS=admin:123secret
```

Create .data folder, create a scripts.json inside. Copy the content from sample-scripts.json
```
mkdir .data
cp sample_scripts.json .data/scripts.json
```

Run cms and open localhost:3000/admin and enter the credentials from the USERS env variable.
```
npm run build
npm start
```

#### Update CSS

```bash
sass --update sass/:public/css/
```
