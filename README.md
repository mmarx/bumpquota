# bumpquota
Automatically bump quotas for everyone, ignoring users without quota, and users with quotas already higher than the new default quota. Uses repquota, and generates a batch file suitable for input to `setquota -b`.