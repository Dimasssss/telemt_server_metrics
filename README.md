# Server Metrics 2026-03-13 18:49:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 132676.9 (36h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4241177
telemt_connections_bad_total 37748
telemt_handshake_timeouts_total 102884
telemt_upstream_connect_attempt_total 27955
telemt_upstream_connect_success_total 27767
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 27955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12274
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_timeout_total 6012
telemt_me_reconnect_attempts_total 28912
telemt_me_reconnect_success_total 18799
telemt_me_reader_eof_total 20185
telemt_me_idle_close_by_peer_total 20184
telemt_me_route_drop_no_conn_total 1588440
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3876644
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15218
telemt_desync_full_logged_total 4050
telemt_desync_suppressed_total 11168
telemt_desync_frames_bucket_total{bucket="1_2"} 3780
telemt_desync_frames_bucket_total{bucket="3_10"} 5793
telemt_desync_frames_bucket_total{bucket="gt_10"} 5645
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 19382
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18786
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 583
telemt_user_connections_total{user="hello"} 3878813
telemt_user_connections_current{user="hello"} 1552
telemt_user_octets_from_client{user="hello"} 54692769692 (50.94 GB)
telemt_user_octets_to_client{user="hello"} 1216496852237 (1.11 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 405
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 32340.8 (8h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 475347
telemt_connections_bad_total 37178
telemt_handshake_timeouts_total 10829
telemt_upstream_connect_attempt_total 9695
telemt_upstream_connect_success_total 9486
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 9695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3657
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 184
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_timeout_total 1846
telemt_me_reconnect_attempts_total 9248
telemt_me_reconnect_success_total 5837
telemt_me_reader_eof_total 6166
telemt_me_idle_close_by_peer_total 6165
telemt_me_route_drop_no_conn_total 178830
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 413082
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1445
telemt_desync_full_logged_total 383
telemt_desync_suppressed_total 1062
telemt_desync_frames_bucket_total{bucket="1_2"} 290
telemt_desync_frames_bucket_total{bucket="3_10"} 659
telemt_desync_frames_bucket_total{bucket="gt_10"} 496
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 6022
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 5829
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 185
telemt_user_connections_total{user="hello"} 415018
telemt_user_connections_current{user="hello"} 417
telemt_user_octets_from_client{user="hello"} 4367059313 (4.07 GB)
telemt_user_octets_to_client{user="hello"} 129834466092 (120.92 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 162297.4 (45h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3098373
telemt_connections_bad_total 28941
telemt_handshake_timeouts_total 207550
telemt_upstream_connect_attempt_total 36085
telemt_upstream_connect_success_total 36075
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 36085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17284
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3530
telemt_me_reconnect_attempts_total 30216
telemt_me_reconnect_success_total 27660
telemt_me_reader_eof_total 29332
telemt_me_idle_close_by_peer_total 29331
telemt_me_route_drop_no_conn_total 1059085
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2561613
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8619
telemt_desync_full_logged_total 2854
telemt_desync_suppressed_total 5765
telemt_desync_frames_bucket_total{bucket="1_2"} 1406
telemt_desync_frames_bucket_total{bucket="3_10"} 3158
telemt_desync_frames_bucket_total{bucket="gt_10"} 4055
telemt_pool_swap_total 153
telemt_me_writer_removed_unexpected_total 27985
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 27619
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 325
telemt_user_connections_total{user="hello"} 2560913
telemt_user_connections_current{user="hello"} 833
telemt_user_octets_from_client{user="hello"} 42133918000 (39.24 GB)
telemt_user_octets_to_client{user="hello"} 900642563997 (838.79 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 162297.9 (45h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1991549
telemt_connections_bad_total 20409
telemt_handshake_timeouts_total 182702
telemt_upstream_connect_attempt_total 50027
telemt_upstream_connect_success_total 47681
telemt_upstream_connect_fail_total 2209
telemt_upstream_connect_attempts_per_request{bucket="1"} 49753
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19116
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2208
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 12000
telemt_me_reconnect_attempts_total 42727
telemt_me_reconnect_success_total 33740
telemt_me_reader_eof_total 36231
telemt_me_idle_close_by_peer_total 36224
telemt_me_route_drop_no_conn_total 709385
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1644944
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3384
telemt_desync_full_logged_total 1094
telemt_desync_suppressed_total 2290
telemt_desync_frames_bucket_total{bucket="1_2"} 919
telemt_desync_frames_bucket_total{bucket="3_10"} 1379
telemt_desync_frames_bucket_total{bucket="gt_10"} 1086
telemt_pool_swap_total 142
telemt_me_writer_removed_unexpected_total 34295
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 33716
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 555
telemt_user_connections_total{user="hello"} 1649639
telemt_user_connections_current{user="hello"} 563
telemt_user_octets_from_client{user="hello"} 25330486481 (23.59 GB)
telemt_user_octets_to_client{user="hello"} 626649327854 (583.61 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 31734.0 (8h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 514988
telemt_connections_bad_total 4737
telemt_handshake_timeouts_total 5185
telemt_upstream_connect_attempt_total 6969
telemt_upstream_connect_success_total 6737
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 6969
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3553
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_keepalive_timeout_total 953
telemt_me_reconnect_attempts_total 24672
telemt_me_reconnect_success_total 5114
telemt_me_reader_eof_total 5815
telemt_me_idle_close_by_peer_total 5815
telemt_me_route_drop_no_conn_total 195605
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 482707
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1393
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 949
telemt_desync_frames_bucket_total{bucket="1_2"} 434
telemt_desync_frames_bucket_total{bucket="3_10"} 550
telemt_desync_frames_bucket_total{bucket="gt_10"} 409
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5767
telemt_me_refill_failed_total 609
telemt_me_writer_restored_same_endpoint_total 5110
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 653
telemt_user_connections_total{user="hello"} 482670
telemt_user_connections_current{user="hello"} 762
telemt_user_octets_from_client{user="hello"} 5552076840 (5.17 GB)
telemt_user_octets_to_client{user="hello"} 155582723124 (144.90 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 85
```