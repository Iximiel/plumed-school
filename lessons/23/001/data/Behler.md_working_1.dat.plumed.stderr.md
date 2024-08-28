Stderr for source:  Behler.md_working_1.dat   
Download: [zipped raw stdout](Behler.md_working_1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](Behler.md_working_1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action CONTACT_MATRIX with label cmat : No atoms have been read in
[fv-az1427-785:07106] *** Process received signal ***
[fv-az1427-785:07106] Signal: Aborted (6)
[fv-az1427-785:07106] Signal code:  (-6)
[fv-az1427-785:07106] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f4ceda42520]
[fv-az1427-785:07106] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f4ceda969fc]
[fv-az1427-785:07106] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f4ceda42476]
[fv-az1427-785:07106] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f4ceda287f3]
[fv-az1427-785:07106] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f4cedea2b9e]
[fv-az1427-785:07106] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f4cedeae20c]
[fv-az1427-785:07106] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f4cedeae277]
[fv-az1427-785:07106] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f4cedeae52b]
[fv-az1427-785:07106] [ 8] plumed(+0x12f48)[0x559ab8df2f48]
[fv-az1427-785:07106] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f4ceda29d90]
[fv-az1427-785:07106] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f4ceda29e40]
[fv-az1427-785:07106] [11] plumed(+0x131e5)[0x559ab8df31e5]
[fv-az1427-785:07106] *** End of error message ***
</pre>
{% endraw %}
