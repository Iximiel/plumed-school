Stderr for source:  SymmetryFunction.md_working_1.dat   
Download: [zipped raw stdout](SymmetryFunction.md_working_1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](SymmetryFunction.md_working_1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action CONTACT_MATRIX with label c1 : No atoms have been read in
[fv-az1427-785:07439] *** Process received signal ***
[fv-az1427-785:07439] Signal: Aborted (6)
[fv-az1427-785:07439] Signal code:  (-6)
[fv-az1427-785:07439] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fa578242520]
[fv-az1427-785:07439] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fa5782969fc]
[fv-az1427-785:07439] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fa578242476]
[fv-az1427-785:07439] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fa5782287f3]
[fv-az1427-785:07439] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fa5786a2b9e]
[fv-az1427-785:07439] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fa5786ae20c]
[fv-az1427-785:07439] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fa5786ae277]
[fv-az1427-785:07439] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fa5786ae52b]
[fv-az1427-785:07439] [ 8] plumed(+0x12f48)[0x56255a1a6f48]
[fv-az1427-785:07439] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fa578229d90]
[fv-az1427-785:07439] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fa578229e40]
[fv-az1427-785:07439] [11] plumed(+0x131e5)[0x56255a1a71e5]
[fv-az1427-785:07439] *** End of error message ***
</pre>
{% endraw %}
