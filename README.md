# simplebintray
简单化 上传 bintray
> 在你需要上传lib 项目中 build.gradle 添加如下配置即可

详细说明请参考

ext{
    bintrayRepo = 'maven'  //创库名称
    bintrayName = 'Bintrayhelper'  //项目名称

    publishedGroupId = 'com.github.zdongcoding'   //groupid
    libraryName = 'Bintrayhelper'    //
    artifact = 'Bintrayhelper'
    artifact_Id = 'bintrayhelper'
    maturity ='Stable'     //成熟度  stable  development offical experimental
    libraryDescription = '测试  update bintray' //项目描述
    /*项目地址或者issue地址*/
    siteUrl = 'https://github.com/zdongcoding/bintrayhelper'
    gitUrl = 'https://github.com/zdongcoding/bintrayhelper.git'
    issueUrl='https://github.com/zdongcoding/bintrayhelper/issues'
    libraryVersion = '0.1.1'    //版本号
    alllabels = ['android','bintray']
    /*一些开发者信息*/
    developerId = 'zdongcoding'
    developerName = 'zoudong'
    developerEmail = 'zoudongq1990@gmail.com'
     /*一些开源信息*/
    licenseName = 'The Apache Software License, Version 2.0'
    licenseUrl = 'http://www.apache.org/licenses/LICENSE-2.0.txt'
    allLicenses = ["Apache-2.0"]
}
apply from: 'https://raw.githubusercontent.com/zdongcoding/bintrayhelper/master/SimpleBintray.gradle'
