Stderr for source:  Volumes.md_working_3.dat   
Download: [zipped raw stdout](Volumes.md_working_3.dat.plumed.stdout.txt.zip) - [zipped raw stderr](Volumes.md_working_3.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action CONTACT_MATRIX with label cmat : No atoms have been read in
[fv-az1427-785:07359] *** Process received signal ***
[fv-az1427-785:07359] Signal: Aborted (6)
[fv-az1427-785:07359] Signal code:  (-6)
[fv-az1427-785:07359] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f34ae642520]
[fv-az1427-785:07359] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f34ae6969fc]
[fv-az1427-785:07359] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f34ae642476]
[fv-az1427-785:07359] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f34ae6287f3]
[fv-az1427-785:07359] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f34aeaa2b9e]
[fv-az1427-785:07359] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f34aeaae20c]
[fv-az1427-785:07359] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f34aeaae277]
[fv-az1427-785:07359] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f34aeaae52b]
[fv-az1427-785:07359] [ 8] plumed(+0x12f48)[0x55aeff46cf48]
[fv-az1427-785:07359] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f34ae629d90]
[fv-az1427-785:07359] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f34ae629e40]
[fv-az1427-785:07359] [11] plumed(+0x131e5)[0x55aeff46d1e5]
[fv-az1427-785:07359] *** End of error message ***
</pre>
{% endraw %}
