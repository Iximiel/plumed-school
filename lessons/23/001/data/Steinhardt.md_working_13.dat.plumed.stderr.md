Stderr for source:  Steinhardt.md_working_13.dat   
Download: [zipped raw stdout](Steinhardt.md_working_13.dat.plumed.stdout.txt.zip) - [zipped raw stderr](Steinhardt.md_working_13.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action CONTACT_MATRIX with label cmat : No atoms have been read in
[fv-az1427-785:06893] *** Process received signal ***
[fv-az1427-785:06893] Signal: Aborted (6)
[fv-az1427-785:06893] Signal code:  (-6)
[fv-az1427-785:06893] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f0c56642520]
[fv-az1427-785:06893] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f0c566969fc]
[fv-az1427-785:06893] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f0c56642476]
[fv-az1427-785:06893] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f0c566287f3]
[fv-az1427-785:06893] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f0c56aa2b9e]
[fv-az1427-785:06893] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f0c56aae20c]
[fv-az1427-785:06893] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f0c56aae277]
[fv-az1427-785:06893] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f0c56aae52b]
[fv-az1427-785:06893] [ 8] plumed(+0x12f48)[0x55d911cbef48]
[fv-az1427-785:06893] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f0c56629d90]
[fv-az1427-785:06893] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f0c56629e40]
[fv-az1427-785:06893] [11] plumed(+0x131e5)[0x55d911cbf1e5]
[fv-az1427-785:06893] *** End of error message ***
</pre>
{% endraw %}
