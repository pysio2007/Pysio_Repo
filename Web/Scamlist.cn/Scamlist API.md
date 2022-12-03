Scamlist Api得请求方式
GET https://api.scamlist.cn/uuid/{UUID}.json
{UUID} 为我的世界用户UUID
返回值如下：
{
    "name": "",           //用户名
    "UUID": "",      //UUID
    "tag": "",     //标签
    "adduse": "",             //添加者
    "reason": "",           //原因
    "DungeonBlack": "",                  //地牢黑名单层数
    "Dreason": "",              //原因
    "Rank": "",                        //RANK
    "contact": "",                     //联系方式
    "fun": ""                         //当此处为true是 则为娱乐添加 非真正黑名单
}