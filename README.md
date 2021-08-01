# urls
Analysis of dataset containing potentially hazardous urls along with the engines and their detections

1. Parsing
Creating a CSV from the JSON data (too big to upload) containing:
- URL
- FQDN (trim the URL to FQDN)
- number of detection engines
- total scanned engines
- detected engines - only if detected
- scan date

2. Analyzing
- What are the top 10 engines in detection amounts? (detected the largest amount of domains)
- Testing the similarity between FQDNs engines detections (in this part I used the top 10 engines from the last step)
- Using CDF to show what are the percentages of detected URLs by the number of detection engines
