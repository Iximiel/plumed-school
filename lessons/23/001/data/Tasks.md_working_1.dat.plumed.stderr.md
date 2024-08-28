Stderr for source:  Tasks.md_working_1.dat   
Download: [zipped raw stdout](Tasks.md_working_1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](Tasks.md_working_1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action DISTANCE with label d1 : Number of specified atoms should be 2
[fv-az1427-785:06189] *** Process received signal ***
[fv-az1427-785:06189] Signal: Aborted (6)
[fv-az1427-785:06189] Signal code:  (-6)
[fv-az1427-785:06189] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f929d042520]
[fv-az1427-785:06189] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f929d0969fc]
[fv-az1427-785:06189] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f929d042476]
[fv-az1427-785:06189] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f929d0287f3]
[fv-az1427-785:06189] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f929d4a2b9e]
[fv-az1427-785:06189] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f929d4ae20c]
[fv-az1427-785:06189] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f929d4ae277]
[fv-az1427-785:06189] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f929d4ae52b]
[fv-az1427-785:06189] [ 8] plumed(+0x12f48)[0x562e4897bf48]
[fv-az1427-785:06189] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f929d029d90]
[fv-az1427-785:06189] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f929d029e40]
[fv-az1427-785:06189] [11] plumed(+0x131e5)[0x562e4897c1e5]
[fv-az1427-785:06189] *** End of error message ***
</pre>
{% endraw %}
