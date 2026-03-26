aws s3 sync --delete dist s3://narbone/cosplay/siluette

aws cloudfront create-invalidation --distribution-id E1CRXBNC4NYWJB --paths '/\*'
