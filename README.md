# commands
Here, I'll list out the commands I know & use. It'll be ideal place to revise the technologies.
## Linux commands
1. ls
2. cd /path/to/directory
3. pwd
4. mkdir new_directory
5. rmdir empty_directory
6. rm file_name
7. rm -r directory_name
8. cp source_file destination_file
9. mv old_name new_name
10. cat file_name
11. less file_name
12. more file_name
13. head -n 10 file_name
14. tail -n 10 file_name
15. touch new_file
16. chmod 755 file_name
17. chown user:group file_name
18. df -h
19. du -sh directory_name
20. ps aux
21. top
22. htop
23. kill process_id
24. kill -9 process_id
25. pkill process_name
26. uname -a
27. whoami
28. id
29. date
30. cal
31. uptime
32. hostname
33. free -h
34. history
35. man command_name
36. echo "text"
37. echo $PATH
38. export VAR=value
39. alias ll='ls -la'
40. unalias ll
41. which command_name
42. whereis command_name
43. locate file_name
44. find /path -name file_name
45. grep "pattern" file_name
46. grep -r "pattern" directory_name
47. tar -czvf archive_name.tar.gz directory_name
48. tar -xzvf archive_name.tar.gz
49. zip archive_name.zip file_name
50. unzip archive_name.zip
51. wget url
52. curl -O url
53. scp user@remote:/path/to/file /local/path
54. rsync -avz /source /destination
55. ssh user@remote_host
56. ssh-keygen
57. ssh-copy-id user@remote_host
58. sudo command
59. sudo su
60. su - user
61. passwd
62. adduser new_user
63. userdel user_name
64. usermod -aG group_name user_name
65. groupadd group_name
66. groupdel group_name
67. crontab -e
68. crontab -l
69. systemctl status service_name
70. systemctl start service_name
71. systemctl stop service_name
72. systemctl restart service_name
73. systemctl enable service_name
74. systemctl disable service_name
75. journalctl -xe
76. dmesg
77. lspci
78. lsusb
79. lsblk
80. blkid
81. mount /dev/sdX1 /mnt
82. umount /mnt
83. fdisk -l
84. mkfs.ext4 /dev/sdX1
85. fsck /dev/sdX1
86. dd if=/dev/sdX of=/path/to/image.img
87. nano file_name
88. vim file_name
89. emacs file_name
