Stderr for source:  Steinhardt.md_working_11.dat   
Download: [zipped raw stdout](Steinhardt.md_working_11.dat.plumed.stdout.txt.zip) - [zipped raw stderr](Steinhardt.md_working_11.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action CONTACT_MATRIX with label cmat : No atoms have been read in
[fv-az1427-785:06831] *** Process received signal ***
[fv-az1427-785:06831] Signal: Aborted (6)
[fv-az1427-785:06831] Signal code:  (-6)
[fv-az1427-785:06831] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7ff395042520]
[fv-az1427-785:06831] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7ff3950969fc]
[fv-az1427-785:06831] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7ff395042476]
[fv-az1427-785:06831] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7ff3950287f3]
[fv-az1427-785:06831] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7ff3954a2b9e]
[fv-az1427-785:06831] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7ff3954ae20c]
[fv-az1427-785:06831] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7ff3954ae277]
[fv-az1427-785:06831] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7ff3954ae52b]
[fv-az1427-785:06831] [ 8] plumed(+0x12f48)[0x564bf612df48]
[fv-az1427-785:06831] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7ff395029d90]
[fv-az1427-785:06831] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7ff395029e40]
[fv-az1427-785:06831] [11] plumed(+0x131e5)[0x564bf612e1e5]
[fv-az1427-785:06831] *** End of error message ***
</pre>
{% endraw %}
