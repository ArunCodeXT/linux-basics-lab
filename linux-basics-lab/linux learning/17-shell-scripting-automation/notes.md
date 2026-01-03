# 17 — Automation & Cron

## Functions
hello() {
  echo "Hello"
}

## Arguments
echo $1
echo $@

## Cron Jobs
crontab -e
* * * * * /path/script.sh

## Summary
I can write automated scripts and schedule tasks in Linux.
