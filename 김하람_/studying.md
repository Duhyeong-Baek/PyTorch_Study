####DAY1 

torch.randn(데이터 수, 채널), n은 정규분포 의미, 정규분포 랜덤 추출
torch.rand(5,2) -> 2채널을 가진 5개의 데이터

####DAY2

#torch 연결 
X_test = torch.cat([X_test.unsqueeze(dim=2), X2_unsqueeze(dim=2)], dim=2)

model.eval() # test mode로 변경
