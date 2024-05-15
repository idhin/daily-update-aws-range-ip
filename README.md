# AWS IP Ranges

![Update AWS IP Ranges](https://github.com/idhin/daily-update-aws-range-ip/workflows/Update%20AWS%20IP%20Ranges/badge.svg)

This repository contains the most up-to-date IP ranges used by Amazon Web Services (AWS). The IP ranges are updated daily to ensure you have the latest information for your network configurations and security policies.

## Overview

The `aws-range-ip-<date-time>.txt` file contains the current AWS IP ranges, updated every day. This information is fetched automatically from AWS and committed to this repository. The file includes all the IP ranges for AWS services, helping you keep your firewall and security settings up to date.

## Usage

You can download the latest IP ranges file and use it in your network configurations to ensure that your infrastructure recognizes and allows traffic from AWS services.

### Example

Here is an example of how to use the file:

```bash
# Download the latest IP ranges file
wget https://github.com/idhin/daily-update-aws-range-ip/raw/main/aws-range-ip-<latest-date-time>.txt

# View the contents
cat aws-range-ip-<latest-date-time>.txt

## ☕ Support Me

If you wanna buy me some coffee, you can visit:

- [Buy Me a Coffee](https://buymeacoffee.com/rasyidin) (Worldwide) 
- [Saweria](https://saweria.co/rasyidin) (Indonesia)

Thank you for your support! 😊
