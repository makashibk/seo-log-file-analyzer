# SEO Log File Aanalyzer

A fast, browser-based SEO log file analysis tool that helps you understand how search engines, AI bots, and human users crawl your website.

Built for SEO teams, developers, and site owners who want to understand how search engines and other bots crawl their website. Upload your server log files and instantly see detailed insights about bot activity, human traffic, HTTP status codes, crawl budget usage, top crawled pages, errors, and more.

It supports Apache and Nginx combined log formats and helps you identify important crawling patterns, wasted crawl budget, high-traffic URLs, 404s, 5xx errors, redirects, and bot-specific behavior. With interactive charts, filters, and dashboards, it makes log file analysis faster, easier, and more actionable for technical SEO audits.

## Features

- Drag-and-drop log file upload
- Supports Apache and Nginx combined log format
- Multi-file analysis for combined crawl insights
- Bot detection for major search engines, SEO tools, AI bots, and social crawlers
- Interactive dashboards with charts and tables
- Crawl budget analysis
- Top crawled pages and directories
- HTTP status code breakdown
- 404 and 5xx error analysis
- Bot-specific crawl reporting
- URL parameter detection
- Redirect analysis
- Raw log exploration with filters
- CSV export
- Recent project storage in browser localStorage
- Works entirely in the browser

## Why Use SEO Log Analyzer?

Log file analysis is one of the most powerful ways to understand how search engines actually crawl your site.

With SEO Log Analyzer, you can quickly find:

- Which pages search bots crawl most often
- Whether crawl budget is being wasted
- Which URLs return errors or redirects
- How AI bots and SEO tools interact with your site
- What content is receiving the most attention from crawlers

This helps you prioritize technical SEO fixes, improve crawl efficiency, and make better indexing decisions.

## Supported Log Formats

SEO Log Analyzer is built to process common server log formats, including:

- Apache combined logs
- Nginx combined logs

Example format:

```txt
IP - - [date] "METHOD /path HTTP/1.x" STATUS bytes "referer" "user-agent"
