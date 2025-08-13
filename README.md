# CSE135-HW1

We implemented deployment from Github to DigitalOcean using the postpreceive hook method that was on the website linked in the instructions. We had trouble at first since we didn’t realize we needed an actual repository in tandem with the bare repository we made by following the instructions. After thoroughly checking our directories and doing more research, we were able to properly set up the deployment and are able to update our code! We considered installing the pipelines as well to help us streamline our git pushes but we think we'll work on that early into HW2 as we want to focus on completing all of HW1 first. As of right now, we are able to deploy from Github to our server!

# Part 3
<ins>Step 5: </ins>
After doing some research, we enabled the mod deflate and proceeded with enabling the compression. To test our results, we accessed the website and checked inspected element > Network > Html file > Headers, where we saw that the content was encoded using gzip and that there was definitely compression going on.

<ins>Step 6: </ins>
We modified the security.conf file with the specified directives, and verified the header change, as this approach goes beyond simply limiting information disclosure (like ServerTokens alone would do) to actively customize the Server header as required, chaging the configuration to

SecRuleEngine on 

ServerTokens Full

SecServerSignature "CSE135 Server"

# EC
Matomo offers full data ownership, privacy compliance, and powerful insights without relying on third-party trackers like Google Analytics. Unlike cloud-based solutions, Matomo is self-hosted, ensuring your visitor data never leaves your server—critical for GDPR, CCPA, and other privacy regulations. It provides real-time analytics, including visitor demographics, page performance, and conversion tracking, while allowing custom reports, heatmaps, and session recordings. Since it’s open-source, you avoid vendor lock-in and can extend functionality via plugins. Additionally, Matomo blocks known bots and spam traffic, ensuring cleaner data. By using Matomo, businesses and developers maintain transparency, security, and control over their analytics while still gaining actionable insights to optimize their websites.
