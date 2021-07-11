# Membuat bckup database dan recovery dengan sql

![bckup](https://user-images.githubusercontent.com/81977332/125197070-7ddc0b80-e286-11eb-8ba7-a355f91b14a0.JPG)

# backup[ menggunakan mysqldump
]
![dump1](https://user-images.githubusercontent.com/81977332/125197077-816f9280-e286-11eb-9f8f-9bbcab29895b.JPG)

![dump2](https://user-images.githubusercontent.com/81977332/125197078-82a0bf80-e286-11eb-8283-f4d95e25b66c.JPG)

# script cron job untuk backup otomatis jam 12 malam

0 0 * * 7 mysqldump -u root -p910771 yeremiaraul_311910771 > yeremiaraul_311910771_bckdatabases.sql