
<h3 align="center">
 <b>Analyze images with aws rekognition</b>
</h3>
<p align="center">Creating a lambda API to analyze images with AWS Rekognition</p>
<hr>
<br>

### Technologies used

This project was developed with the following technologies:

- [Node.js](https://nodejs.org/en/)
- [Serverless Framework](https://www.serverless.com/)
- [AWS Lambda](https://aws.amazon.com/pt/lambda/)
- [AWS Rekognition](https://aws.amazon.com/pt/rekognition/?blog-cards.sort-by=item.additionalFields.createdDate&blog-cards.sort-order=desc)
- [AWS Translate](https://aws.amazon.com/pt/translate/)
- [Axios](https://axios-http.com/docs/intro)


### ⚙ How to run this project

### Prerequisites

Before you start, you will need to have the following tools installed on your machine:

<b>[Git](https://git-scm.com)</b>

<b>[Node.js](https://nodejs.org/en/)</b>

<b>[Serverless Framework](https://www.serverless.com/)</b>

<b>AWS Credentions confidured</b>


And you will also need an editor, I recommend <b>[VSCode](https://code.visualstudio.com/)</b>

### 🧭 Running

```bash
# Clone this repository
$ git clone https://github.com/lucasrocha1999/analyze-images-with-aws-rekognition.git

# Go to the project folder in terminal/cmd
$ cd analyze-images-with-aws-rekognition

# Install the dependencies
$ npm i or yarn

# Calling the function locally
$ sls invoke local -f img-analysis --path request.json

# Deploying the Application
$ sls deploy

# Calling the function via lambda
$ sls invoke -f img-analysis --path request.json --log

```

### License

EThis project is under the MIT license. See the file [LICENSE](LICENSE) for more details.

---
