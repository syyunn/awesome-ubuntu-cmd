# awesome-ubuntu-cmd
commonly used ubuntu cmds

# Storage
df / -h

# IPConfig
curl https://ipinfo.io/ip

# SCP 
scp test_data.json zachary@192.168.0.3:/home/zachary/

# GPU Watch
watch -n0.1 nvidia-smi

# Count the findings
find -name '*.zip' | wc -l

# Delete with finds (use when arglist limit occurs)
find . -name "*.xml" -delete
