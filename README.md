# subtitle-overlap-fixersu
This is a slightly modded version of nimatrueway/subtitle-overlap-fixer.go, a big thank you! Salute!
It basically :
Removes empty subtitles
Removes subtitles with very very short duration (<150ms)
Removes first line of a subtitle, if it is the same as the last line of previous subtitle
Sets to-time‍‍‍‍‍‍‍ of the previous subtitle to from-time of the next subtitle - 1 milliseconds if they overlap time-wise.
Suitable to handle the Youtube overlapped subtitles.

这是对 nimatrueway/subtitle-overlap-fixer.go 的一个轻微修改版本，优化了输出文件的扩展名问题，
非常感谢原作者！致敬！
它的主要功能包括：
删除空的字幕条目
删除持续时间非常短的字幕（小于 150 毫秒）
如果某条字幕的第一行与上一条字幕的最后一行相同，则删除该第一行
如果两条字幕在时间上有重叠，则将前一条字幕的结束时间设置为后一条字幕的开始时间减去 1 毫秒
适合处理YouTube 重叠字幕
