Stderr for source:  Steinhardt.md_working_10.dat   
Download: [zipped raw stdout](Steinhardt.md_working_10.dat.plumed.stdout.txt.zip) - [zipped raw stderr](Steinhardt.md_working_10.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action PRINT with label @2 : action lq6 has no component named lq6 (hint! the components in this actions are: )
[fv-az1427-785:06800] *** Process received signal ***
[fv-az1427-785:06800] Signal: Aborted (6)
[fv-az1427-785:06800] Signal code:  (-6)
[fv-az1427-785:06800] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f2569a42520]
[fv-az1427-785:06800] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f2569a969fc]
[fv-az1427-785:06800] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f2569a42476]
[fv-az1427-785:06800] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f2569a287f3]
[fv-az1427-785:06800] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f2569ea2b9e]
[fv-az1427-785:06800] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f2569eae20c]
[fv-az1427-785:06800] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f2569eae277]
[fv-az1427-785:06800] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f2569eae52b]
[fv-az1427-785:06800] [ 8] plumed(+0x12f48)[0x55d1ed53df48]
[fv-az1427-785:06800] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f2569a29d90]
[fv-az1427-785:06800] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f2569a29e40]
[fv-az1427-785:06800] [11] plumed(+0x131e5)[0x55d1ed53e1e5]
[fv-az1427-785:06800] *** End of error message ***
</pre>
{% endraw %}
