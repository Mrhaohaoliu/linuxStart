default = 'ubuntu'
        dcd = open('/var/lib/ubuntu_dist_channel').read()
    'ubuntu': { 
        'bug_pattern_url': 'http://people.canonical.com/~ubuntu-archive/bugpatterns/bugpatterns.xml',
        'dupdb_url': 'http://people.canonical.com/~ubuntu-archive/apport-duplicates',
        'distro': 'ubuntu',
        'bug_pattern_url': 'http://people.canonical.com/~ubuntu-archive/bugpatterns/bugpatterns.xml',
search updates ubuntu built-in
env CRASH_DB_URL=https://daisy.ubuntu.com
author "Dimitri John Ledkov <xnox@ubuntu.com> and Jamie Strandboge <jamie@ubuntu.com>"
        if ! compare_and_save_debsums apparmor-easyprof-ubuntu ; then
        if ! compare_and_save_debsums apparmor-easyprof-ubuntu-snappy ; then
    # Note: if apparmor-easyprof-ubuntu md5sums didn't match up above,
author "Clint Byrum <clint@ubuntu.com>"
author		"Chuck Short <zulcss@ubuntu.com>"
# https://wiki.ubuntu.com/SecurityTeam/Roadmap/KernelHardening#ptrace
    <allow own="com.ubuntu.Mountall.Server" />
    <allow send_destination="com.ubuntu.Mountall.Server"
    <allow send_destination="com.ubuntu.Mountall.Server"
	   send_interface="com.ubuntu.Mountall0_1.Server" />
    <allow send_destination="com.ubuntu.Mountall.Server"
    <allow send_destination="com.ubuntu.Mountall.Server"
    <allow send_destination="com.ubuntu.Mountall.Server"
    <allow own="com.ubuntu.USBCreator"/>
    <allow send_destination="com.ubuntu.USBCreator" 
           send_interface="com.ubuntu.USBCreator"/>
    <allow send_destination="com.ubuntu.USBCreator" 
    <allow send_destination="com.ubuntu.USBCreator" 
                <allow own="com.ubuntu.SystemService"/>
    		<allow send_destination="com.ubuntu.SystemService"
                       send_interface="com.ubuntu.SystemService"/>
                <allow send_destination="com.ubuntu.SystemService"
                <allow send_destination="com.ubuntu.SystemService"
    <allow own="com.ubuntu.WhoopsiePreferences"/>
    <allow send_destination="com.ubuntu.WhoopsiePreferences" 
           send_interface="com.ubuntu.WhoopsiePreferences"/>
    <allow send_destination="com.ubuntu.WhoopsiePreferences" 
    <allow send_destination="com.ubuntu.WhoopsiePreferences" 
    <allow own="com.ubuntu.Upstart" />
    <allow send_destination="com.ubuntu.Upstart"
    <allow send_destination="com.ubuntu.Upstart"
	   send_interface="com.ubuntu.Upstart0_6" />
    <allow send_destination="com.ubuntu.Upstart"
	   send_interface="com.ubuntu.Upstart0_6.Job" />
    <allow send_destination="com.ubuntu.Upstart"
	   send_interface="com.ubuntu.Upstart0_6.Instance" />
    <allow send_destination="com.ubuntu.Upstart"
    <allow send_destination="com.ubuntu.Upstart"
    <allow send_destination="com.ubuntu.Upstart"
    <allow send_destination="com.ubuntu.Upstart"
	   send_interface="com.ubuntu.Upstart0_6"
    <allow send_destination="com.ubuntu.Upstart"
	   send_interface="com.ubuntu.Upstart0_6"
    <allow send_destination="com.ubuntu.Upstart"
	   send_interface="com.ubuntu.Upstart0_6.Job"
    <allow send_destination="com.ubuntu.Upstart"
	   send_interface="com.ubuntu.Upstart0_6.Job"
    <allow send_destination="com.ubuntu.Upstart"
	   send_interface="com.ubuntu.Upstart0_6.Job"
    <allow own="com.ubuntu.SoftwareProperties"/>
    <allow send_destination="com.ubuntu.SoftwareProperties"
           send_interface="com.ubuntu.SoftwareProperties"/>
    <allow send_destination="com.ubuntu.SoftwareProperties"
    <allow send_destination="com.ubuntu.DeviceDriver"
                <allow own="com.ubuntu.LanguageSelector"/>
    		<allow send_interface="com.ubuntu.LanguageSelector"/>
		<allow receive_interface="com.ubuntu.LanguageSelector"
   		       receive_sender="com.ubuntu.LanguageSelector"/>
		<allow send_destination="com.ubuntu.LanguageSelector"
		<allow send_destination="com.ubuntu.LanguageSelector"
#FallbackNTP=ntp.ubuntu.com
[ubuntu]
ScreenshotUrl=http://screenshots.ubuntu.com
