## VPC
### VPCの作成
![VPCの作成](./image/vpc_create.png)

## EC2
### EC2の作成
![EC2の作成](./image/ec2_create.png)

### EC2のセキュリティグループ
0.0.0.0/0はすべての通信を許可するネットワーク範囲なので、今回は自分のPCからのみアクセスが可能なネットワークに設定しました。
![EC2のセキュリティグループ](./image/ec2_security.png)

## RDS
### RDSの作成
![RDSの作成](./image/rds_create.png)

### RDSのセキュリティグループ
RDSもEC2と同様にセキュリティ対策として、さきほど作成したEC2からのみアクセスが可能なようにネットワークを設定しました。
![RDSのセキュリティグループ](./image/rds_security.png)

## EC2からRDSに接続
EC2から正常に接続されているのが確認できる。
![EC2からRDSに接続](./image/ec2_rds.png)