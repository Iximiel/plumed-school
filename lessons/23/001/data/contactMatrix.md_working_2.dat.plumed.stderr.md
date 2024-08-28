Stderr for source:  contactMatrix.md_working_2.dat   
Download: [zipped raw stdout](contactMatrix.md_working_2.dat.plumed.stdout.txt.zip) - [zipped raw stderr](contactMatrix.md_working_2.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action CONTACT_MATRIX with label c1 : No atoms have been read in
[fv-az1427-785:05930] *** Process received signal ***
[fv-az1427-785:05930] Signal: Aborted (6)
[fv-az1427-785:05930] Signal code:  (-6)
[fv-az1427-785:05930] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f05af642520]
[fv-az1427-785:05930] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f05af6969fc]
[fv-az1427-785:05930] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f05af642476]
[fv-az1427-785:05930] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f05af6287f3]
[fv-az1427-785:05930] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f05afaa2b9e]
[fv-az1427-785:05930] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f05afaae20c]
[fv-az1427-785:05930] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f05afaae277]
[fv-az1427-785:05930] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f05afaae52b]
[fv-az1427-785:05930] [ 8] plumed(+0x12f48)[0x55bce63d4f48]
[fv-az1427-785:05930] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f05af629d90]
[fv-az1427-785:05930] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f05af629e40]
[fv-az1427-785:05930] [11] plumed(+0x131e5)[0x55bce63d51e5]
[fv-az1427-785:05930] *** End of error message ***
</pre>
{% endraw %}
