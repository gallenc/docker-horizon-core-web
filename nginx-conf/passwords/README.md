The passwords file sets passwords for NGINX basic authentication
By default username john password s3cr3t
you should delete and replace this file with a new password file

See https://www.elastic.co/blog/playing-http-tricks-nginx

Generate password with
 
printf "john:$(openssl passwd -crypt s3cr3t)\n" > passwords
