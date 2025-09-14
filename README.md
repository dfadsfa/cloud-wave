# 1. Streamlit Sample Project


TEST

성능검증


<details>
  <summary>👉 부하테스트 모니터링 지표 /summary>

Ready 파드 : 클러스터 전체에서 Ready 상태인 파드 수의 합계
  sum(kube_pod_status_ready{condition="true"})

Ready 노드 : 실제로 노드를 몇 개까지 늘렸는지 확인하는 지표
  sum(kube_node_status_condition{condition="Ready", status="true"})
</details>

