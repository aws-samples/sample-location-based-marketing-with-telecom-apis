# Location Based Marketing using Telecom Camara APIs and Amazon Pinpoint

Location-based marketing (LBM) is a specialized form of targeted marketing that focuses on reaching customers at the right place and time. Traditional LBM relies on GPS technology, which requires customers to install mobile apps and consent to location sharing. This requirement often creates barriers to adoption and growth, while GPS usage can significantly drain device batteries, leading users to disable it when possible. In contrast, Communication Service Providers (CSPs) can determine subscriber locations through cell tower data, and with 5G technology, they can now achieve even greater accuracy, including indoor locations where GPS typically struggles. The introduction of Camara Network APIs has further simplified the process for CSPs to provide location notifications to businesses and facilitate location-based marketing campaigns.

In this blog, we demonstrate how businesses can implement a cost-effective, serverless solution for real-time location-based marketing by combining CSP Camara Network APIs with Amazon Pinpoint service.

Please refer to the blog (link will be added) for detailed solution and implementation steps.

**Note**: This git repository and the related blog is an example starter project designed to provide a demonstration and basis for builders to create their own solutions. It should not be considered Production-ready. The code should be modified for production use, for example, by including input format validation and more sophisticated error handling. Moreover, when invoking in production the actual Telco Camara API, that is here simulated through a AWS Lambda implementation, a proper authorisation mechanism must be implemented according to the API Telco Operator security rules.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.
