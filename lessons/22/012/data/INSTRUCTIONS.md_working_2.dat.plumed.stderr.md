Stderr for source:  INSTRUCTIONS.md_working_2.dat   
Download: [zipped raw stdout](INSTRUCTIONS.md_working_2.dat.plumed.stdout.txt.zip) - [zipped raw stderr](INSTRUCTIONS.md_working_2.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label s : keyword SIGMA could not be read correctly
[fv-az1427-785:08854] *** Process received signal ***
[fv-az1427-785:08854] Signal: Aborted (6)
[fv-az1427-785:08854] Signal code:  (-6)
[fv-az1427-785:08854] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7ffba8242520]
[fv-az1427-785:08854] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7ffba82969fc]
[fv-az1427-785:08854] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7ffba8242476]
[fv-az1427-785:08854] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7ffba82287f3]
[fv-az1427-785:08854] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7ffba86a2b9e]
[fv-az1427-785:08854] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7ffba86ae20c]
[fv-az1427-785:08854] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7ffba86ae277]
[fv-az1427-785:08854] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7ffba86ae52b]
[fv-az1427-785:08854] [ 8] plumed(+0x12f48)[0x55b1d3452f48]
[fv-az1427-785:08854] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7ffba8229d90]
[fv-az1427-785:08854] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7ffba8229e40]
[fv-az1427-785:08854] [11] plumed(+0x131e5)[0x55b1d34531e5]
[fv-az1427-785:08854] *** End of error message ***
</pre>
{% endraw %}
