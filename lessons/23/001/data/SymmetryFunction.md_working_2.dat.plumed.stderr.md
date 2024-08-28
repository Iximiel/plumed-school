Stderr for source:  SymmetryFunction.md_working_2.dat   
Download: [zipped raw stdout](SymmetryFunction.md_working_2.dat.plumed.stdout.txt.zip) - [zipped raw stderr](SymmetryFunction.md_working_2.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action CONTACT_MATRIX with label c1 : No atoms have been read in
[fv-az1427-785:07469] *** Process received signal ***
[fv-az1427-785:07469] Signal: Aborted (6)
[fv-az1427-785:07469] Signal code:  (-6)
[fv-az1427-785:07469] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f66dac42520]
[fv-az1427-785:07469] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f66dac969fc]
[fv-az1427-785:07469] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f66dac42476]
[fv-az1427-785:07469] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f66dac287f3]
[fv-az1427-785:07469] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f66db0a2b9e]
[fv-az1427-785:07469] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f66db0ae20c]
[fv-az1427-785:07469] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f66db0ae277]
[fv-az1427-785:07469] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f66db0ae52b]
[fv-az1427-785:07469] [ 8] plumed(+0x12f48)[0x56024f73bf48]
[fv-az1427-785:07469] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f66dac29d90]
[fv-az1427-785:07469] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f66dac29e40]
[fv-az1427-785:07469] [11] plumed(+0x131e5)[0x56024f73c1e5]
[fv-az1427-785:07469] *** End of error message ***
</pre>
{% endraw %}
