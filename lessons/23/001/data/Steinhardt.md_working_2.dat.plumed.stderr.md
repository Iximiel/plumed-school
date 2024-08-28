Stderr for source:  Steinhardt.md_working_2.dat   
Download: [zipped raw stdout](Steinhardt.md_working_2.dat.plumed.stdout.txt.zip) - [zipped raw stderr](Steinhardt.md_working_2.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action CONTACT_MATRIX with label cmat : No atoms have been read in
[fv-az1427-785:06553] *** Process received signal ***
[fv-az1427-785:06553] Signal: Aborted (6)
[fv-az1427-785:06553] Signal code:  (-6)
[fv-az1427-785:06553] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f84de842520]
[fv-az1427-785:06553] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f84de8969fc]
[fv-az1427-785:06553] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f84de842476]
[fv-az1427-785:06553] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f84de8287f3]
[fv-az1427-785:06553] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f84deca2b9e]
[fv-az1427-785:06553] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f84decae20c]
[fv-az1427-785:06553] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f84decae277]
[fv-az1427-785:06553] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f84decae52b]
[fv-az1427-785:06553] [ 8] plumed(+0x12f48)[0x56370db20f48]
[fv-az1427-785:06553] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f84de829d90]
[fv-az1427-785:06553] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f84de829e40]
[fv-az1427-785:06553] [11] plumed(+0x131e5)[0x56370db211e5]
[fv-az1427-785:06553] *** End of error message ***
</pre>
{% endraw %}
