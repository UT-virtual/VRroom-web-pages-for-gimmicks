# 自己紹介ギミック用データ
自己紹介ギミックに必要なデータがおかれています。

自分の自己紹介を置きたい場合、member_data内にまだ使われていないindex(0以上)のフォルダを作成し、その中にicon.pngとして正方形のアイコンを、image.pngとして16:9の自己紹介画像を置いてください。

その後member_list.jsonに自分の名前とindex、何期か(term)を追記してください。

member_listの形式
```json
[
    {
        ...
    },
    ...
    {            
        "data_index":42,
        "name":"example",
        "term":6
    },
    ...
]
```
indexが事前に生成されるURLの数を以上になってしまうとエラーが起きます。VRroomのUnityProject内で生成するURLの数を増やしてください。
