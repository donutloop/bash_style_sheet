# Bash Style Sheet

## Kill port

```bash
kill $(lsof -t -i:4568)
```

## Process - report a snapshot of the current processes and grep for a port

```bash
  ps aux | grep 3356
```

## netstat  - Print network connections, routing tables, interface statistics, masquerade con‐nections, and multicast memberships

```bash 
netstat -nltp
```
