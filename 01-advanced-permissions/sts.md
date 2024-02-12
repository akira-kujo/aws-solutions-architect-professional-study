### Security Token Service

* Generates temporary credentials (sts:AssumeRole*)
* STS' can expire
* Requested by an Identity (AWS via IAM Role or an External via Google login, FB etc)


STS uses **permissions policy** to generate temporary credentials
  * Permissions Policies are generated in JSON format

<img src="./images/sts.jpg"/>