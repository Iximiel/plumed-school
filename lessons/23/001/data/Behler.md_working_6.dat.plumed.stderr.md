Stderr for source:  Behler.md_working_6.dat   
Download: [zipped raw stdout](Behler.md_working_6.dat.plumed.stdout.txt.zip) - [zipped raw stderr](Behler.md_working_6.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action CONTACT_MATRIX with label cmat : No atoms have been read in
[fv-az1427-785:07262] *** Process received signal ***
[fv-az1427-785:07262] Signal: Aborted (6)
[fv-az1427-785:07262] Signal code:  (-6)
[fv-az1427-785:07262] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f3c07c42520]
[fv-az1427-785:07262] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f3c07c969fc]
[fv-az1427-785:07262] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f3c07c42476]
[fv-az1427-785:07262] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f3c07c287f3]
[fv-az1427-785:07262] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f3c080a2b9e]
[fv-az1427-785:07262] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f3c080ae20c]
[fv-az1427-785:07262] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f3c080ae277]
[fv-az1427-785:07262] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f3c080ae52b]
[fv-az1427-785:07262] [ 8] plumed(+0x12f48)[0x5563c8452f48]
[fv-az1427-785:07262] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f3c07c29d90]
[fv-az1427-785:07262] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f3c07c29e40]
[fv-az1427-785:07262] [11] plumed(+0x131e5)[0x5563c84531e5]
[fv-az1427-785:07262] *** End of error message ***
</pre>
{% endraw %}
