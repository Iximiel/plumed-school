Stderr for source:  histograms.md_working_9.dat   
Download: [zipped raw stdout](histograms.md_working_9.dat.plumed.stdout.txt.zip) - [zipped raw stderr](histograms.md_working_9.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action DISTANCES with label d1 : keyword ATOMS could not be read correctly
[fv-az1427-785:08184] *** Process received signal ***
[fv-az1427-785:08184] Signal: Aborted (6)
[fv-az1427-785:08184] Signal code:  (-6)
[fv-az1427-785:08184] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f0693c42520]
[fv-az1427-785:08184] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f0693c969fc]
[fv-az1427-785:08184] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f0693c42476]
[fv-az1427-785:08184] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f0693c287f3]
[fv-az1427-785:08184] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f06940a2b9e]
[fv-az1427-785:08184] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f06940ae20c]
[fv-az1427-785:08184] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f06940ae277]
[fv-az1427-785:08184] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f06940ae52b]
[fv-az1427-785:08184] [ 8] plumed(+0x12f48)[0x5623ec4bff48]
[fv-az1427-785:08184] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f0693c29d90]
[fv-az1427-785:08184] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f0693c29e40]
[fv-az1427-785:08184] [11] plumed(+0x131e5)[0x5623ec4c01e5]
[fv-az1427-785:08184] *** End of error message ***
</pre>
{% endraw %}
