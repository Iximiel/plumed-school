Stderr for source:  RMSD.md_working_1.dat   
Download: [zipped raw stdout](RMSD.md_working_1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](RMSD.md_working_1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action CONSTANT with label v : cannot understand the following words from the input line : NCOLS=12, NROWS=2
[fv-az1427-785:08430] *** Process received signal ***
[fv-az1427-785:08430] Signal: Aborted (6)
[fv-az1427-785:08430] Signal code:  (-6)
[fv-az1427-785:08430] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f90d8042520]
[fv-az1427-785:08430] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f90d80969fc]
[fv-az1427-785:08430] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f90d8042476]
[fv-az1427-785:08430] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f90d80287f3]
[fv-az1427-785:08430] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f90d84a2b9e]
[fv-az1427-785:08430] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f90d84ae20c]
[fv-az1427-785:08430] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f90d84ae277]
[fv-az1427-785:08430] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f90d84ae52b]
[fv-az1427-785:08430] [ 8] plumed(+0x12f48)[0x563cbb3aaf48]
[fv-az1427-785:08430] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f90d8029d90]
[fv-az1427-785:08430] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f90d8029e40]
[fv-az1427-785:08430] [11] plumed(+0x131e5)[0x563cbb3ab1e5]
[fv-az1427-785:08430] *** End of error message ***
</pre>
{% endraw %}
