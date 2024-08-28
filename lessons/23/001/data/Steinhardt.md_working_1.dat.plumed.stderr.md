Stderr for source:  Steinhardt.md_working_1.dat   
Download: [zipped raw stdout](Steinhardt.md_working_1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](Steinhardt.md_working_1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action CONTACT_MATRIX with label cmat : No atoms have been read in
[fv-az1427-785:06522] *** Process received signal ***
[fv-az1427-785:06522] Signal: Aborted (6)
[fv-az1427-785:06522] Signal code:  (-6)
[fv-az1427-785:06522] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f13d5a42520]
[fv-az1427-785:06522] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f13d5a969fc]
[fv-az1427-785:06522] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f13d5a42476]
[fv-az1427-785:06522] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f13d5a287f3]
[fv-az1427-785:06522] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f13d5ea2b9e]
[fv-az1427-785:06522] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f13d5eae20c]
[fv-az1427-785:06522] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f13d5eae277]
[fv-az1427-785:06522] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f13d5eae52b]
[fv-az1427-785:06522] [ 8] plumed(+0x12f48)[0x557468892f48]
[fv-az1427-785:06522] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f13d5a29d90]
[fv-az1427-785:06522] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f13d5a29e40]
[fv-az1427-785:06522] [11] plumed(+0x131e5)[0x5574688931e5]
[fv-az1427-785:06522] *** End of error message ***
</pre>
{% endraw %}
