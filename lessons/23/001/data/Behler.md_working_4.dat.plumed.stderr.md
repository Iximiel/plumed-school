Stderr for source:  Behler.md_working_4.dat   
Download: [zipped raw stdout](Behler.md_working_4.dat.plumed.stdout.txt.zip) - [zipped raw stderr](Behler.md_working_4.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action DISTANCE with label d1 : Number of specified atoms should be 2
[fv-az1427-785:07202] *** Process received signal ***
[fv-az1427-785:07202] Signal: Aborted (6)
[fv-az1427-785:07202] Signal code:  (-6)
[fv-az1427-785:07202] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fc567442520]
[fv-az1427-785:07202] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fc5674969fc]
[fv-az1427-785:07202] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fc567442476]
[fv-az1427-785:07202] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fc5674287f3]
[fv-az1427-785:07202] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fc5678a2b9e]
[fv-az1427-785:07202] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fc5678ae20c]
[fv-az1427-785:07202] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fc5678ae277]
[fv-az1427-785:07202] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fc5678ae52b]
[fv-az1427-785:07202] [ 8] plumed(+0x12f48)[0x564ecb015f48]
[fv-az1427-785:07202] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fc567429d90]
[fv-az1427-785:07202] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fc567429e40]
[fv-az1427-785:07202] [11] plumed(+0x131e5)[0x564ecb0161e5]
[fv-az1427-785:07202] *** End of error message ***
</pre>
{% endraw %}
