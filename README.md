# portfolio


# architecture
1.
Add a side-car nginx container to act as a reverse-proxy to prove the access to the static content of php application assets. The dynamic part is done with php-fpm

2. Blue-green EKS cluster solution to keep baseline up-to date and implement short service windows, safe roll-back

3. Create helm configuration of newcore dss 