# Hugo Personal Blog

Hugo Personal Blog built with Nixon Theme

## Getting Started

Install Hugo
https://gohugo.io/getting-started/installing/

`git clone https://github.com/SmartTechie/hugo-personal-blog.git blog`
`cd blog`

### Configuration

- Open **config.toml** file and make following changes
  - Change following according to your site info 
    - baseurl         (line# 1)
    - title           (line# 3)
    - copyright       (line# 5)
    - [author]        (line# 13)
    - copyright_years (line# 22)
    - domain_name     (line# 24)
    - personal_site   (line# 25)
    - name            (line# 28)
    - short_bio       (line# 31)
  - Give your social media accounts name in [params.facebook] [params.linkedin] [params.twitter]
  - If you have any licencing then fill [params.license] in **config.toml**

- Change your favicon by replacing old favicon in *C:\Hugo\Sites\domain.com\static\faviocn.ico*

### How to write post

`hugo new post/post-name.md`
`cd content\post`
- edit post-name.md
- change the **draft: true** to **draft: false**.
- Now aftre three hyphens *---* write down your markdown for the post and save it.

For markdown visit https://en.support.wordpress.com/markdown-quick-reference/
For hugo shortcodes visit https://gohugo.io/content-management/shortcodes/

For generating static site run command `hugo` in main directory (e.g. blog)
Your site will be generated in *public* diretory



  
