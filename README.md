# Saori Skeleton
## Installation
```sh
composer create-project hrgruri/saori-skeleton blog
```

## Usage
```sh
php saori

# initialize
php saori init

# generate draft file
php saori draft first_article

# edit draft file
vim draft/first_article/article.md
vim draft/first_article/config.json

# post
php saori post first_article

# generate static site
php saori build
```

## Setting
contents/config.json
```json
{
    "id"        :   "username",
    "local"     :   "http://localhost:8000",
    "title"     :   "Example Blog",
    "author"    :   "John Doe",
    "theme"     :   "saori",
    "lang"      :   "en",
    "link"      :   {
        "github"    :   "https://github.com",
        "twitter"   :   "https://twitter.com"
    }
}
```
