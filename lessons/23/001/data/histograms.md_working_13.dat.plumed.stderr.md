Stderr for source:  histograms.md_working_13.dat   
Download: [zipped raw stdout](histograms.md_working_13.dat.plumed.stdout.txt.zip) - [zipped raw stderr](histograms.md_working_13.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: KDE LABEL=hA_kde ARG=x GRID_MIN=0.0 GRID_MAX=3.0 GRID_BIN=100 BANDWIDTH=0.1 HEIGHTS=fh
Maybe a missing space or a typo?
[fv-az1427-785:08308] *** Process received signal ***
[fv-az1427-785:08308] Signal: Aborted (6)
[fv-az1427-785:08308] Signal code:  (-6)
[fv-az1427-785:08308] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fe546a42520]
[fv-az1427-785:08308] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fe546a969fc]
[fv-az1427-785:08308] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fe546a42476]
[fv-az1427-785:08308] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fe546a287f3]
[fv-az1427-785:08308] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fe546ea2b9e]
[fv-az1427-785:08308] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fe546eae20c]
[fv-az1427-785:08308] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fe546eae277]
[fv-az1427-785:08308] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fe546eae52b]
[fv-az1427-785:08308] [ 8] plumed(+0x12f48)[0x5629faab1f48]
[fv-az1427-785:08308] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fe546a29d90]
[fv-az1427-785:08308] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fe546a29e40]
[fv-az1427-785:08308] [11] plumed(+0x131e5)[0x5629faab21e5]
[fv-az1427-785:08308] *** End of error message ***
</pre>
{% endraw %}
