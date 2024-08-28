Stderr for source:  histograms.md_working_12.dat   
Download: [zipped raw stdout](histograms.md_working_12.dat.plumed.stdout.txt.zip) - [zipped raw stderr](histograms.md_working_12.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: KDE LABEL=hA_kde ARG=x GRID_MIN=0.0 GRID_MAX=3.0 GRID_BIN=100 BANDWIDTH=0.1 VOLUMES=f
Maybe a missing space or a typo?
[fv-az1427-785:08278] *** Process received signal ***
[fv-az1427-785:08278] Signal: Aborted (6)
[fv-az1427-785:08278] Signal code:  (-6)
[fv-az1427-785:08278] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f6a60a42520]
[fv-az1427-785:08278] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f6a60a969fc]
[fv-az1427-785:08278] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f6a60a42476]
[fv-az1427-785:08278] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f6a60a287f3]
[fv-az1427-785:08278] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f6a60ea2b9e]
[fv-az1427-785:08278] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f6a60eae20c]
[fv-az1427-785:08278] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f6a60eae277]
[fv-az1427-785:08278] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f6a60eae52b]
[fv-az1427-785:08278] [ 8] plumed(+0x12f48)[0x5607e8ae0f48]
[fv-az1427-785:08278] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f6a60a29d90]
[fv-az1427-785:08278] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f6a60a29e40]
[fv-az1427-785:08278] [11] plumed(+0x131e5)[0x5607e8ae11e5]
[fv-az1427-785:08278] *** End of error message ***
</pre>
{% endraw %}
