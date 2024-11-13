To start your app in cluster mode, use PM2's -i flag. This flag specifies how many instances or copies to create. You can set it to:
1️⃣ -i max to automatically use the maximum number of CPU cores, or
2️⃣ A specific number, like -i 4, if you want exactly 4 instances.

After the bash command PM2 will:
1️⃣ Start one instance on each core,
2️⃣ Distribute incoming requests across the instances, and
3️⃣ Show a dashboard with each instance’s status.
