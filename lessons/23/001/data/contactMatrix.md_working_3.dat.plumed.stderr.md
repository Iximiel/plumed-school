Stderr for source:  contactMatrix.md_working_3.dat   
Download: [zipped raw stdout](contactMatrix.md_working_3.dat.plumed.stdout.txt.zip) - [zipped raw stderr](contactMatrix.md_working_3.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action CONTACT_MATRIX with label c1 : No atoms have been read in
[fv-az1427-785:05976] *** Process received signal ***
[fv-az1427-785:05976] Signal: Aborted (6)
[fv-az1427-785:05976] Signal code:  (-6)
[fv-az1427-785:05976] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f6737842520]
[fv-az1427-785:05976] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f67378969fc]
[fv-az1427-785:05976] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f6737842476]
[fv-az1427-785:05976] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f67378287f3]
[fv-az1427-785:05976] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f6737ca2b9e]
[fv-az1427-785:05976] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f6737cae20c]
[fv-az1427-785:05976] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f6737cae277]
[fv-az1427-785:05976] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f6737cae52b]
[fv-az1427-785:05976] [ 8] plumed(+0x12f48)[0x55a49c1a3f48]
[fv-az1427-785:05976] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f6737829d90]
[fv-az1427-785:05976] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f6737829e40]
[fv-az1427-785:05976] [11] plumed(+0x131e5)[0x55a49c1a41e5]
[fv-az1427-785:05976] *** End of error message ***
</pre>
{% endraw %}
