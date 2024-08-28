Stderr for source:  INSTRUCTIONS.md_working_2.dat   
Download: [zipped raw stdout](INSTRUCTIONS.md_working_2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](INSTRUCTIONS.md_working_2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : keyword SIGMA could not be read correctly
[fv-az1427-785:08862] *** Process received signal ***
[fv-az1427-785:08862] Signal: Aborted (6)
[fv-az1427-785:08862] Signal code:  (-6)
[fv-az1427-785:08862] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fb0da642520]
[fv-az1427-785:08862] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fb0da6969fc]
[fv-az1427-785:08862] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fb0da642476]
[fv-az1427-785:08862] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fb0da6287f3]
[fv-az1427-785:08862] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fb0daaa2b9e]
[fv-az1427-785:08862] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fb0daaae20c]
[fv-az1427-785:08862] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fb0daaae277]
[fv-az1427-785:08862] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fb0daaae52b]
[fv-az1427-785:08862] [ 8] plumed_master(+0x14274)[0x55aff6a6a274]
[fv-az1427-785:08862] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fb0da629d90]
[fv-az1427-785:08862] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fb0da629e40]
[fv-az1427-785:08862] [11] plumed_master(+0x14ed5)[0x55aff6a6aed5]
[fv-az1427-785:08862] *** End of error message ***
</pre>
{% endraw %}
