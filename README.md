# NestJS Udemy Course (Frontend)

**Title**: NestJS Zero to Hero - Modern TypeScript Back-end Development

**Link**: https://www.udemy.com/course/nestjs-zero-to-hero/

## Development

Run command `npm run start`

**Link**: http://localhost:3001

## Production server

**Link**: http://udemy-nestjs-frontend-bucket.s3-website.us-east-2.amazonaws.com/

### Note:
When you are going to make a deployment, you need to edit file  `udemy-nestjs-frontend\src\services\base-http.service.js` and replace the value of the key `BASE_URL`, with de production backend server url `http://udemynestjsbackendelasticbeanstalk-env-2.eba-n6pypz3u.us-east-2.elasticbeanstalk.com`.

After that, you need to run the command `npm run build` and upload the files inside the `build` folder to the `S3` instance. 