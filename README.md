# C# Log Into Azure App Insight
1) Create App Insight Service in Azure
2) Copy the connection string from App Insight Overview
3) Paste the connectionstring in TelemetryConfiguration instance. Eg., like below.
 configuration.ConnectionString = "InstrumentationKey=b0f0b144-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx;IngestionEndpoint=https://westus-9.in.app....";
4) All set, execute..
