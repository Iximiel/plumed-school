Stderr for source:  INSTRUCTIONS.md_working_5.dat   
Download: [zipped raw stdout](INSTRUCTIONS.md_working_5.dat.plumed.stdout.txt.zip) - [zipped raw stderr](INSTRUCTIONS.md_working_5.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action MATHEVAL with label diff : cannot find action named cv (hint! the actions with value in this ActionSet are: q6 )
[fv-az1427-785:08947] *** Process received signal ***
[fv-az1427-785:08947] Signal: Aborted (6)
[fv-az1427-785:08947] Signal code:  (-6)
[fv-az1427-785:08947] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f1acca42520]
[fv-az1427-785:08947] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f1acca969fc]
[fv-az1427-785:08947] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f1acca42476]
[fv-az1427-785:08947] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f1acca287f3]
[fv-az1427-785:08947] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f1accea2b9e]
[fv-az1427-785:08947] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f1acceae20c]
[fv-az1427-785:08947] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f1acceae277]
[fv-az1427-785:08947] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f1acceae52b]
[fv-az1427-785:08947] [ 8] plumed(+0x12f48)[0x55d72d90df48]
[fv-az1427-785:08947] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f1acca29d90]
[fv-az1427-785:08947] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f1acca29e40]
[fv-az1427-785:08947] [11] plumed(+0x131e5)[0x55d72d90e1e5]
[fv-az1427-785:08947] *** End of error message ***
</pre>
{% endraw %}
