Stderr for source:  INSTRUCTIONS.md_working_6.dat   
Download: [zipped raw stdout](INSTRUCTIONS.md_working_6.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](INSTRUCTIONS.md_working_6.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action UPPER_WALLS with label @s9 : cannot find action named cv (hint! the actions with value in this ActionSet are: timestep kBT posx posy posz Masses Charges Box driver )
[fv-az1427-785:08986] *** Process received signal ***
[fv-az1427-785:08986] Signal: Aborted (6)
[fv-az1427-785:08986] Signal code:  (-6)
[fv-az1427-785:08986] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f82df242520]
[fv-az1427-785:08986] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f82df2969fc]
[fv-az1427-785:08986] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f82df242476]
[fv-az1427-785:08986] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f82df2287f3]
[fv-az1427-785:08986] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f82df6a2b9e]
[fv-az1427-785:08986] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f82df6ae20c]
[fv-az1427-785:08986] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f82df6ae277]
[fv-az1427-785:08986] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f82df6ae52b]
[fv-az1427-785:08986] [ 8] plumed_master(+0x14274)[0x555e8bfcb274]
[fv-az1427-785:08986] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f82df229d90]
[fv-az1427-785:08986] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f82df229e40]
[fv-az1427-785:08986] [11] plumed_master(+0x14ed5)[0x555e8bfcbed5]
[fv-az1427-785:08986] *** End of error message ***
</pre>
{% endraw %}
