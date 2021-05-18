# Pizzeria The King
Thank so this pratical experience, I could understand the immediatekey differences between GitHub Pages,  AWS S3 and Azure

### Links
* [GitHub Pages hosted website]()
* [AWS SE Hosted Website](https://pizzeria-king-webapp.s3.eu-west-2.amazonaws.com/pizzeria-the-king/index.html)
* [Azure Hosted Website]() 

Time required to host your website:
- GitHub: 2 minutes.
- AWS: 6/7 minutes.
- Azure

The repository/bucket must be public:
- GitHub: ✔️
- AWS: ❌
- Azure

Free hosting:
- GitHub: ✔️
- AWS: ❗Independently from the use, you have 1 year of free tier powered by AWS. With less than 15GB of data transfer, less than 20K GET requests and 2K PUT requested (for a month), Your S3 instance will be free during all the free year tier.
- Azure
- 
Ability to choose the Datacenter Region in order to decrease latency:
- GitHub: ❌
- AWS: ✔️
- Azure

Frequent updates:
- GitHub: ✔️ it's enough to push in the default branch of the repository and see the changes within 2/3 minutes most of the time.
- AWS: ❗ If you want to be fast and avoid to update all the files manually via the AWS Portal, you have to set up a pipeline to trigger a lambda function every time that a push/commit has been made to the S3 bucket and simply wait for that the lambda function will update anything for you.
- Azure

## Thecnologies and tools used
HTML, CSS, JavaScript, Bootstrap, Git;
## The template has been provided by
* Colorlib; 
## Contributor to the project
* [Davide Pollicino](https://github.com/omonimus1/)

## Resources
* [Host website on GitHUb pages](https://medium.com/any-writers/how-to-host-a-static-website-on-github-for-free-f47b12790775)
* [Host WebSite in AWS](https://www.freecodecamp.org/news/a-beginners-guide-on-how-to-host-a-static-site-with-aws/)
* [Host WebSite in Azure](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blob-static-website-how-to?tabs=azure-portal)
