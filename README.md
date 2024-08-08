# Stock Analysis Assistant

## Overview
This project is a simple demonstration of Amazon Bedrock and the Anthropic Claude 3 Sonnet model integrated with Langchain and Streamlit. It aims to provide insights and analysis of stock data using advanced AI capabilities. For more details, please refer to the following links:
- [Amazon Bedrock](https://aws.amazon.com/bedrock/)
- [Claude 3](https://www.anthropic.com/news/claude-3-family)

## Directory Structure
```
Stock-Analysis-Assistant/
├── img/
├── pages/
│   ├── base.py
│   ├── company.json
│   ├── Home.py
│   ├── libs.py
│   ├── main.py
├── nohup.out
├── README.md
├── requirements.txt
├── SP500.csv
├── tickers.csv
```

## To View Demo and Sample Data
- Access the `demo` folder for the demo video.
- Access the `samples` folder for sample videos.

## Setup Instructions
1. **Install Python:**
   - Follow the [Python installation guide](https://docs.python-guide.org/starting/install3/linux/).

2. **Set Up Python Environment:**
   - Follow the [Python virtual environment setup guide](https://docs.python-guide.org/dev/virtualenvs/#virtualenvironments-ref).

3. **Set Up AWS CLI:**
   - Follow the [AWS CLI quickstart guide](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-quickstart.html).

4. **Clone the Repository:**
   ```sh
   git clone https://github.com/awsstudygroup/Stock-Analysis-Agent-with-Amazon-Bedrock/
   cd Stock-Analysis-Agent-with-Amazon-Bedrock
   pip3 install -r requirements.txt
   streamlit run Home.py --server.port 8080
   ```

## Architecture
![Architecture](./img/Architecture.png)

## Learn More About Prompt and Claude 3
- [Introduction to Prompt Design](https://docs.anthropic.com/claude/docs/introduction-to-prompt-design)
- [Claude 3 Model Card](https://www-cdn.anthropic.com/de8ba9b01c9ab7cbabf5c33b80b7bbc618857627/Model_Card_Claude_3.pdf)

## Contributing
We welcome contributions to Stock Analysis Assistant! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Make your changes and commit them with clear and descriptive messages.
4. Push your changes to your forked repository.
5. Open a pull request to the main repository.

## License
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

## Contact
For any questions or feedback, please reach out to the project maintainers at [email@example.com](mailto:email@example.com).
