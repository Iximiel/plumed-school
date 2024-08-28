Stderr for source:  Sprint.md_working_2.dat   
Download: [zipped raw stdout](Sprint.md_working_2.dat.plumed.stdout.txt.zip) - [zipped raw stderr](Sprint.md_working_2.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action CONTACT_MATRIX with label s1_mat : No atoms have been read in
[fv-az1427-785:06457] *** Process received signal ***
[fv-az1427-785:06457] Signal: Aborted (6)
[fv-az1427-785:06457] Signal code:  (-6)
[fv-az1427-785:06457] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f555d042520]
[fv-az1427-785:06457] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f555d0969fc]
[fv-az1427-785:06457] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f555d042476]
[fv-az1427-785:06457] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f555d0287f3]
[fv-az1427-785:06457] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f555d4a2b9e]
[fv-az1427-785:06457] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f555d4ae20c]
[fv-az1427-785:06457] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f555d4ae277]
[fv-az1427-785:06457] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f555d4ae52b]
[fv-az1427-785:06457] [ 8] plumed(+0x12f48)[0x5583ab43cf48]
[fv-az1427-785:06457] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f555d029d90]
[fv-az1427-785:06457] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f555d029e40]
[fv-az1427-785:06457] [11] plumed(+0x131e5)[0x5583ab43d1e5]
[fv-az1427-785:06457] *** End of error message ***
</pre>
{% endraw %}
