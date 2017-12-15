---

copyright:
  years: 2015, 2017
lastupdated: "2017-10-27"

---

<!-- Attribute definitions -->
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:pre: .pre}

# Streaming Analytics での Beam アプリケーションのデプロイ
{: #develop_beam_apps}

ローカル {{site.data.keyword.streamsshort}} 開発環境で Beam アプリケーションを開発し、そのアプリケーションを {{site.data.keyword.streaminganalyticsshort}} にデプロイできるようになりました。
{:shortdesc}

{{site.data.keyword.streamsshort}} Runner for Apache Beam は、{{site.data.keyword.streamsshort}} 環境で Beam パイプラインを実行します。Streams Runner を使用して起動される Beam アプリケーションは、後で {{site.data.keyword.streaminganalyticsshort}} でデプロイしてモニターできる Streams Application Bundle (SAB) ファイルに変換されます。

{{site.data.keyword.Bluemix_notm}} 上の {{site.data.keyword.streaminganalyticsshort}} サービスに Beam アプリケーションをサブミットするには、サービスの資格情報とその他の情報を保持する JSON 形式の VCAP ファイルを作成する必要があります。

1. Streams ローカル環境で、ツールキット ($STREAMS_BEAM_RUNNER/samples) をインストールしたサンプル・サブフォルダーにナビゲートして、template.vcap ファイルを新しいファイルにコピーします。このファイルにわかりやすい名前とファイル拡張子 .vcap を付けます。
1. [{{site.data.keyword.streaminganalyticsshort}} サービス](/docs/services/StreamingAnalytics/r_vcap_services.md)の資格情報をコピーして、作成した VCAP ファイルにこの資格情報を貼り付けて、以下の行を置き換えます。
```
 <REMOVE THIS LINE AND INSERT CREDENTIALS HERE>
 ```
1. ご使用の開発環境で Beam アプリケーションが正しく実行されることを確認します。Streams Runner で Beam アプリケーションを起動すると、このアプリケーションは Streams Application Bundle (SAB) ファイルに変換されます。
1. Beam アプリケーションに関連付けられた SAB ファイルを {{site.data.keyword.streaminganalyticsshort}} にサブミットします。

これで、アプリケーションはクラウドにデプロイされました。{{site.data.keyword.streaminganalyticsshort}} サービスを使用して、アプリケーションをモニターできます。

{{site.data.keyword.streaminganalyticsshort}} での Beam アプリケーションのデプロイおよびモニターについて詳しくは、[Streams Runner for Apache Beam ](https://ibmstreams.github.io/streamsx.documentation/docs/beamrunner/beamrunner-1-intro/)を参照してください。