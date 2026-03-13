# Server Metrics 2026-03-13 22:59:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 147674.8 (41h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4552006
telemt_connections_bad_total 38380
telemt_handshake_timeouts_total 107445
telemt_upstream_connect_attempt_total 30894
telemt_upstream_connect_success_total 30683
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 30894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13688
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_timeout_total 6644
telemt_me_reconnect_attempts_total 31109
telemt_me_reconnect_success_total 20984
telemt_me_reader_eof_total 22500
telemt_me_idle_close_by_peer_total 22499
telemt_me_route_drop_no_conn_total 1721072
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4170488
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16585
telemt_desync_full_logged_total 4466
telemt_desync_suppressed_total 12119
telemt_desync_frames_bucket_total{bucket="1_2"} 4130
telemt_desync_frames_bucket_total{bucket="3_10"} 6341
telemt_desync_frames_bucket_total{bucket="gt_10"} 6114
telemt_pool_swap_total 125
telemt_me_writer_removed_unexpected_total 21603
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 20971
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 619
telemt_user_connections_total{user="hello"} 4172419
telemt_user_connections_current{user="hello"} 641
telemt_user_octets_from_client{user="hello"} 61232432568 (57.03 GB)
telemt_user_octets_to_client{user="hello"} 1318138526965 (1.20 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 47338.4 (13h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 602103
telemt_connections_bad_total 43831
telemt_handshake_timeouts_total 12526
telemt_upstream_connect_attempt_total 13392
telemt_upstream_connect_success_total 13159
telemt_upstream_connect_fail_total 233
telemt_upstream_connect_attempts_per_request{bucket="1"} 13392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5338
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 23
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 233
telemt_me_keepalive_timeout_total 1915
telemt_me_reconnect_attempts_total 12185
telemt_me_reconnect_success_total 8752
telemt_me_reader_eof_total 9261
telemt_me_idle_close_by_peer_total 9260
telemt_me_route_drop_no_conn_total 218521
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 520135
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1643
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 712
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 8985
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 8744
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 233
telemt_user_connections_total{user="hello"} 522068
telemt_user_connections_current{user="hello"} 218
telemt_user_octets_from_client{user="hello"} 5759382425 (5.36 GB)
telemt_user_octets_to_client{user="hello"} 169731530632 (158.07 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 177295.2 (49h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3303549
telemt_connections_bad_total 31830
telemt_handshake_timeouts_total 221099
telemt_upstream_connect_attempt_total 39326
telemt_upstream_connect_success_total 39305
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 39326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18588
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10304
telemt_me_reconnect_attempts_total 35128
telemt_me_reconnect_success_total 30176
telemt_me_reader_eof_total 32021
telemt_me_idle_close_by_peer_total 32020
telemt_me_route_drop_no_conn_total 1132979
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2743924
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8998
telemt_desync_full_logged_total 3028
telemt_desync_suppressed_total 5970
telemt_desync_frames_bucket_total{bucket="1_2"} 1512
telemt_desync_frames_bucket_total{bucket="3_10"} 3260
telemt_desync_frames_bucket_total{bucket="gt_10"} 4226
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 30618
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 30135
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 442
telemt_user_connections_total{user="hello"} 2743182
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 44674974308 (41.61 GB)
telemt_user_octets_to_client{user="hello"} 969902465805 (903.29 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 177297.8 (49h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2167896
telemt_connections_bad_total 22843
telemt_handshake_timeouts_total 224887
telemt_upstream_connect_attempt_total 55209
telemt_upstream_connect_success_total 52760
telemt_upstream_connect_fail_total 2312
telemt_upstream_connect_attempts_per_request{bucket="1"} 54935
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20962
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2311
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20345
telemt_me_reconnect_attempts_total 45943
telemt_me_reconnect_success_total 36924
telemt_me_reader_eof_total 39601
telemt_me_idle_close_by_peer_total 39594
telemt_me_route_drop_no_conn_total 758208
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1763189
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3795
telemt_desync_full_logged_total 1216
telemt_desync_suppressed_total 2579
telemt_desync_frames_bucket_total{bucket="1_2"} 1002
telemt_desync_frames_bucket_total{bucket="3_10"} 1587
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 154
telemt_me_writer_removed_unexpected_total 37524
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 36900
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 600
telemt_user_connections_total{user="hello"} 1769072
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 27321750019 (25.45 GB)
telemt_user_octets_to_client{user="hello"} 660689025026 (615.31 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 46731.3 (12h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 647217
telemt_connections_bad_total 7841
telemt_handshake_timeouts_total 6699
telemt_upstream_connect_attempt_total 10591
telemt_upstream_connect_success_total 10256
telemt_upstream_connect_fail_total 335
telemt_upstream_connect_attempts_per_request{bucket="1"} 10591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4906
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5325
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 335
telemt_me_keepalive_timeout_total 1432
telemt_me_reconnect_attempts_total 37639
telemt_me_reconnect_success_total 7922
telemt_me_reader_eof_total 8996
telemt_me_idle_close_by_peer_total 8995
telemt_me_route_drop_no_conn_total 245781
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 603317
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1598
telemt_desync_full_logged_total 500
telemt_desync_suppressed_total 1098
telemt_desync_frames_bucket_total{bucket="1_2"} 484
telemt_desync_frames_bucket_total{bucket="3_10"} 624
telemt_desync_frames_bucket_total{bucket="gt_10"} 490
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 8922
telemt_me_refill_failed_total 925
telemt_me_writer_restored_same_endpoint_total 7917
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1000
telemt_user_connections_total{user="hello"} 603224
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 9653401604 (8.99 GB)
telemt_user_octets_to_client{user="hello"} 198136749812 (184.53 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 37
```