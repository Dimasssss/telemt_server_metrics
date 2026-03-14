# Server Metrics 2026-03-14 04:47:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 168532.3 (46h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4782234
telemt_connections_bad_total 39900
telemt_handshake_timeouts_total 110015
telemt_upstream_connect_attempt_total 35561
telemt_upstream_connect_success_total 35326
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 35561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15932
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_timeout_total 7299
telemt_me_reconnect_attempts_total 34736
telemt_me_reconnect_success_total 24593
telemt_me_reader_eof_total 26397
telemt_me_idle_close_by_peer_total 26396
telemt_me_route_drop_no_conn_total 1812241
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4387083
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16917
telemt_desync_full_logged_total 4572
telemt_desync_suppressed_total 12345
telemt_desync_frames_bucket_total{bucket="1_2"} 4222
telemt_desync_frames_bucket_total{bucket="3_10"} 6460
telemt_desync_frames_bucket_total{bucket="gt_10"} 6235
telemt_pool_swap_total 147
telemt_me_writer_removed_unexpected_total 25259
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 24580
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 666
telemt_user_connections_total{user="hello"} 4388652
telemt_user_connections_current{user="hello"} 920
telemt_user_octets_from_client{user="hello"} 64134218684 (59.73 GB)
telemt_user_octets_to_client{user="hello"} 1383077914637 (1.26 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 68195.9 (18h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 746205
telemt_connections_bad_total 52840
telemt_handshake_timeouts_total 13629
telemt_upstream_connect_attempt_total 18762
telemt_upstream_connect_success_total 18502
telemt_upstream_connect_fail_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 18762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8005
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 260
telemt_me_keepalive_timeout_total 2107
telemt_me_reconnect_attempts_total 16536
telemt_me_reconnect_success_total 13082
telemt_me_reader_eof_total 13892
telemt_me_idle_close_by_peer_total 13891
telemt_me_route_drop_no_conn_total 246970
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 593489
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1777
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 1254
telemt_desync_frames_bucket_total{bucket="1_2"} 373
telemt_desync_frames_bucket_total{bucket="3_10"} 789
telemt_desync_frames_bucket_total{bucket="gt_10"} 615
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 13368
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 13074
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 595440
telemt_user_connections_current{user="hello"} 261
telemt_user_octets_from_client{user="hello"} 6355932281 (5.92 GB)
telemt_user_octets_to_client{user="hello"} 198281974596 (184.66 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 198152.6 (55h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3443075
telemt_connections_bad_total 37127
telemt_handshake_timeouts_total 227687
telemt_upstream_connect_attempt_total 44814
telemt_upstream_connect_success_total 44792
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 44813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20979
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 239
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10607
telemt_me_reconnect_attempts_total 39577
telemt_me_reconnect_success_total 34606
telemt_me_reader_eof_total 36770
telemt_me_idle_close_by_peer_total 36769
telemt_me_route_drop_no_conn_total 1177202
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2868532
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9498
telemt_desync_full_logged_total 3191
telemt_desync_suppressed_total 6307
telemt_desync_frames_bucket_total{bucket="1_2"} 1643
telemt_desync_frames_bucket_total{bucket="3_10"} 3439
telemt_desync_frames_bucket_total{bucket="gt_10"} 4416
telemt_pool_swap_total 188
telemt_me_writer_removed_unexpected_total 35088
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 34565
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 482
telemt_user_connections_total{user="hello"} 2867745
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 45811839252 (42.67 GB)
telemt_user_octets_to_client{user="hello"} 1028165816101 (957.55 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 198155.2 (55h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2308403
telemt_connections_bad_total 23083
telemt_handshake_timeouts_total 260590
telemt_upstream_connect_attempt_total 61974
telemt_upstream_connect_success_total 59498
telemt_upstream_connect_fail_total 2339
telemt_upstream_connect_attempts_per_request{bucket="1"} 61700
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35568
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23764
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2338
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20462
telemt_me_reconnect_attempts_total 51640
telemt_me_reconnect_success_total 42600
telemt_me_reader_eof_total 45685
telemt_me_idle_close_by_peer_total 45678
telemt_me_route_drop_no_conn_total 783195
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1831030
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3884
telemt_desync_full_logged_total 1251
telemt_desync_suppressed_total 2633
telemt_desync_frames_bucket_total{bucket="1_2"} 1045
telemt_desync_frames_bucket_total{bucket="3_10"} 1614
telemt_desync_frames_bucket_total{bucket="gt_10"} 1225
telemt_pool_swap_total 176
telemt_me_writer_removed_unexpected_total 43251
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 42576
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 651
telemt_user_connections_total{user="hello"} 1836987
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 27805795051 (25.90 GB)
telemt_user_octets_to_client{user="hello"} 674638247378 (628.31 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 67588.7 (18h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 736098
telemt_connections_bad_total 7978
telemt_handshake_timeouts_total 8855
telemt_upstream_connect_attempt_total 17399
telemt_upstream_connect_success_total 16936
telemt_upstream_connect_fail_total 463
telemt_upstream_connect_attempts_per_request{bucket="1"} 17399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8905
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 463
telemt_me_keepalive_timeout_total 1537
telemt_me_reconnect_attempts_total 52315
telemt_me_reconnect_success_total 13554
telemt_me_reader_eof_total 15109
telemt_me_idle_close_by_peer_total 15108
telemt_me_route_drop_no_conn_total 281042
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 686920
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1734
telemt_desync_full_logged_total 547
telemt_desync_suppressed_total 1187
telemt_desync_frames_bucket_total{bucket="1_2"} 514
telemt_desync_frames_bucket_total{bucket="3_10"} 677
telemt_desync_frames_bucket_total{bucket="gt_10"} 543
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 14879
telemt_me_refill_failed_total 1207
telemt_me_writer_restored_same_endpoint_total 13549
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1325
telemt_user_connections_total{user="hello"} 686788
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 12440969276 (11.59 GB)
telemt_user_octets_to_client{user="hello"} 221962641936 (206.72 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 51
```