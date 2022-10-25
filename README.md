## Detección de fraude en transacciones de tarjeta de crédito usando Amazon Fraud Detector

Amazon Fraud Detector provides a fully managed service that uses machine learning for detecting potential fraud in real time (e.g. online payment and identity fraud, the creation of fake accounts, loyalty account and promotion code abuse, etc.), based on the same technology used by Amazon.com—with no machine learning experience required. With Amazon Fraud Detector, customers use their historical data of both fraudulent and legitimate transactions to build, train, and deploy machine learning models that provide real-time, low-latency fraud risk predictions. 


[Amazon Fraud Detector](https://docs.aws.amazon.com/es_es/frauddetector/latest/ug/what-is-frauddetector.html) emplea machine learning para detectar posibles fraudes en transacciones en tiempo real, como pagos online o creación de cuentas falsas. Es un servicio completamente administrado, basado en la misma tecnología que Amazon.com. Los usuarios del servicio únicamente necesitan datos históricos de transacciones fraudulentas y legítimas para construir, entrenar y lanzar el modelo.

En este [notebook](./fraud-detector.ipynb) entrenaremos a Fraud Detector para identificar fraude en transacciones con tarjeta de crédito.