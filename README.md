# Server Metrics 2026-03-13 11:56:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 107882.1 (29h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3188453
telemt_connections_bad_total 36473
telemt_handshake_timeouts_total 55715
telemt_upstream_connect_attempt_total 21397
telemt_upstream_connect_success_total 21282
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 21397
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10279
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 1502
telemt_me_reconnect_attempts_total 25999
telemt_me_reconnect_success_total 15919
telemt_me_reader_eof_total 17107
telemt_me_idle_close_by_peer_total 17106
telemt_me_route_drop_no_conn_total 1181770
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2918749
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12469
telemt_desync_full_logged_total 3232
telemt_desync_suppressed_total 9237
telemt_desync_frames_bucket_total{bucket="1_2"} 3189
telemt_desync_frames_bucket_total{bucket="3_10"} 4685
telemt_desync_frames_bucket_total{bucket="gt_10"} 4595
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 16452
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 15906
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 533
telemt_user_connections_total{user="hello"} 2918686
telemt_user_connections_current{user="hello"} 1678
telemt_user_octets_from_client{user="hello"} 40498574428 (37.72 GB)
telemt_user_octets_to_client{user="hello"} 944914195788 (880.02 GB)
telemt_user_unique_ips_current{user="hello"} 454
telemt_user_unique_ips_recent_window{user="hello"} 246
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 7545.7 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99296
telemt_connections_bad_total 6163
telemt_handshake_timeouts_total 2321
telemt_upstream_connect_attempt_total 2002
telemt_upstream_connect_success_total 1932
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 2002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 926
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 2715
telemt_me_reconnect_success_total 1489
telemt_me_reader_eof_total 1555
telemt_me_idle_close_by_peer_total 1555
telemt_me_route_drop_no_conn_total 34750
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88379
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 173
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 122
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1536
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 1482
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 88406
telemt_user_connections_current{user="hello"} 572
telemt_user_octets_from_client{user="hello"} 883851696 (842.91 MB)
telemt_user_octets_to_client{user="hello"} 21529257756 (20.05 GB)
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 137502.3 (38h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2434755
telemt_connections_bad_total 25563
telemt_handshake_timeouts_total 162571
telemt_upstream_connect_attempt_total 31372
telemt_upstream_connect_success_total 31362
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 31372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14850
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 118
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1985
telemt_me_reconnect_attempts_total 26719
telemt_me_reconnect_success_total 24174
telemt_me_reader_eof_total 25620
telemt_me_idle_close_by_peer_total 25619
telemt_me_route_drop_no_conn_total 808286
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1970213
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6577
telemt_desync_full_logged_total 2123
telemt_desync_suppressed_total 4454
telemt_desync_frames_bucket_total{bucket="1_2"} 1040
telemt_desync_frames_bucket_total{bucket="3_10"} 2395
telemt_desync_frames_bucket_total{bucket="gt_10"} 3142
telemt_pool_swap_total 127
telemt_me_writer_removed_unexpected_total 24454
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 24133
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 1969628
telemt_user_connections_current{user="hello"} 992
telemt_user_octets_from_client{user="hello"} 33339838448 (31.05 GB)
telemt_user_octets_to_client{user="hello"} 705416521421 (656.97 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 284
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 137502.7 (38h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1546413
telemt_connections_bad_total 17370
telemt_handshake_timeouts_total 103062
telemt_upstream_connect_attempt_total 44635
telemt_upstream_connect_success_total 42320
telemt_upstream_connect_fail_total 2178
telemt_upstream_connect_attempts_per_request{bucket="1"} 44361
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16644
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2177
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11588
telemt_me_reconnect_attempts_total 38584
telemt_me_reconnect_success_total 29621
telemt_me_reader_eof_total 31856
telemt_me_idle_close_by_peer_total 31849
telemt_me_route_drop_no_conn_total 549346
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1291578
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2422
telemt_desync_full_logged_total 814
telemt_desync_suppressed_total 1608
telemt_desync_frames_bucket_total{bucket="1_2"} 664
telemt_desync_frames_bucket_total{bucket="3_10"} 920
telemt_desync_frames_bucket_total{bucket="gt_10"} 838
telemt_pool_swap_total 118
telemt_me_writer_removed_unexpected_total 30118
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 29597
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 497
telemt_user_connections_total{user="hello"} 1296301
telemt_user_connections_current{user="hello"} 552
telemt_user_octets_from_client{user="hello"} 19394780837 (18.06 GB)
telemt_user_octets_to_client{user="hello"} 507097840366 (472.27 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 6939.1 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98167
telemt_connections_bad_total 494
telemt_handshake_timeouts_total 551
telemt_upstream_connect_attempt_total 1454
telemt_upstream_connect_success_total 1407
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 1454
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 813
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 7711
telemt_me_reconnect_success_total 1017
telemt_me_reader_eof_total 1196
telemt_me_idle_close_by_peer_total 1196
telemt_me_route_drop_no_conn_total 37736
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93904
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 350
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 227
telemt_desync_frames_bucket_total{bucket="1_2"} 177
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_me_writer_removed_unexpected_total 1218
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 1013
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 93900
telemt_user_connections_current{user="hello"} 735
telemt_user_octets_from_client{user="hello"} 1112873532 (1.04 GB)
telemt_user_octets_to_client{user="hello"} 30579281788 (28.48 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 86
```