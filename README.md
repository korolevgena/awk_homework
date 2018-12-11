# awk_homework

Command to test this homework:

awk '
BEGIN { for (i=1;i<200;i++)
print int (101*rand())
}' | awk -f histogram