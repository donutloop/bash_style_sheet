# Bash Style Sheet

## Process got killed by linux 

```bash
dmesg -T| grep -E -i -B100 'killed process'
```

## Kill port

```bash
k
ill $(lsof -t -i:4568)
```

## Process - report a snapshot of the current processes and grep for a port

```bash
  ps aux | grep 3356
```

## netstat  - Print network connections, routing tables, interface statistics, masquerade con‐nections, and multicast memberships

```bash 
netstat -nltp
```

## Grep error of systemd service 

```bash
journalctl --no-pager -u {{service_name}} -b | grep "error"
```

## ssh

```bash
ssh -i key.pem user@host
```

## timestamp for migrations

```bash
$(date +%Y%m%d%H%M%S)
```
