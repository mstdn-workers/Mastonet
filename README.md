※本家Mastonetとの差分  
■ローカルタイムラインのストリーム取得機能の追加  
GetLocalStreaming()メソッドを使用しローカルタイムラインをストリームで取得可能。  
使い方はGetPublicStreaming()と同様。  

■deleteイベント発生時のバグ修正  
本家Mastonetではdeleteイベントの処理が不適切であったため修正。  

その他の機能・仕様は本家Mastonetから改変なし。  

# Masto.NET

![Build status](https://glacasa.visualstudio.com/_apis/public/build/definitions/b2cc08b3-5c47-4294-b016-434c80d4059c/43/badge)
[![NuGet](https://img.shields.io/nuget/v/Mastonet.svg)](https://www.nuget.org/packages/Mastonet/)

Masto.NET is a .net standard library for Mastodon written in C#.

## Sample

If you prefer to browse code, you can go the the sample project : https://github.com/glacasa/Mastonet.SampleApp

## Nuget

The package is available on Nuget : https://www.nuget.org/packages/Mastonet 

Run the following command in the Package Manager Console  :

    Install-Package Mastonet


## Getting started

Read the docs :

- [How to use](https://github.com/glacasa/Mastonet/blob/master/DOC.md)
- [API Overview](https://github.com/glacasa/Mastonet/blob/master/API.md)