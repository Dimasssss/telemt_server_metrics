# Server Metrics 2026-03-15 15:01:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 60396.5 (16h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1909500
telemt_connections_bad_total 102443
telemt_handshake_timeouts_total 21873
telemt_upstream_connect_attempt_total 11997
telemt_upstream_connect_success_total 11946
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 11997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5668
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 13806
telemt_me_reconnect_success_total 8915
telemt_me_reader_eof_total 9537
telemt_me_idle_close_by_peer_total 9537
telemt_me_route_drop_no_conn_total 655345
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1617413
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6161
telemt_desync_full_logged_total 1711
telemt_desync_suppressed_total 4450
telemt_desync_frames_bucket_total{bucket="1_2"} 1521
telemt_desync_frames_bucket_total{bucket="3_10"} 2374
telemt_desync_frames_bucket_total{bucket="gt_10"} 2266
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 9213
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 8904
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 298
telemt_user_connections_total{user="hello"} 1616955
telemt_user_connections_current{user="hello"} 2466
telemt_user_octets_from_client{user="hello"} 23230653232 (21.64 GB)
telemt_user_octets_to_client{user="hello"} 629382145552 (586.16 GB)
telemt_user_unique_ips_current{user="hello"} 677
telemt_user_unique_ips_recent_window{user="hello"} 370
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 60397.3 (16h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 767284
telemt_connections_bad_total 41312
telemt_handshake_timeouts_total 58432
telemt_upstream_connect_attempt_total 15253
telemt_upstream_connect_success_total 15180
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 15253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8111
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6931
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 11886
telemt_me_reconnect_success_total 11791
telemt_me_reader_eof_total 12460
telemt_me_idle_close_by_peer_total 12460
telemt_me_route_drop_no_conn_total 191510
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 580697
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1994
telemt_desync_full_logged_total 690
telemt_desync_suppressed_total 1304
telemt_desync_frames_bucket_total{bucket="1_2"} 739
telemt_desync_frames_bucket_total{bucket="3_10"} 731
telemt_desync_frames_bucket_total{bucket="gt_10"} 524
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 11941
telemt_me_writer_restored_same_endpoint_total 11779
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 580944
telemt_user_connections_current{user="hello"} 864
telemt_user_octets_from_client{user="hello"} 8062158279 (7.51 GB)
telemt_user_octets_to_client{user="hello"} 218302406948 (203.31 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 60397.4 (16h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1684184
telemt_connections_bad_total 47182
telemt_handshake_timeouts_total 169285
telemt_upstream_connect_attempt_total 13310
telemt_upstream_connect_success_total 13246
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 13310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6355
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 11428
telemt_me_reconnect_success_total 10169
telemt_me_reader_eof_total 10772
telemt_me_idle_close_by_peer_total 10772
telemt_me_route_drop_no_conn_total 449234
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1027862
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2538
telemt_desync_full_logged_total 939
telemt_desync_suppressed_total 1599
telemt_desync_frames_bucket_total{bucket="1_2"} 586
telemt_desync_frames_bucket_total{bucket="3_10"} 983
telemt_desync_frames_bucket_total{bucket="gt_10"} 969
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10351
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 10150
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 1023867
telemt_user_connections_current{user="hello"} 1376
telemt_user_octets_from_client{user="hello"} 14898259656 (13.88 GB)
telemt_user_octets_to_client{user="hello"} 369141793532 (343.79 GB)
telemt_user_unique_ips_current{user="hello"} 395
telemt_user_unique_ips_recent_window{user="hello"} 224
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 60397.2 (16h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 807570
telemt_connections_bad_total 74144
telemt_handshake_timeouts_total 41389
telemt_upstream_connect_attempt_total 167515
telemt_upstream_connect_success_total 167013
telemt_upstream_connect_fail_total 502
telemt_upstream_connect_attempts_per_request{bucket="1"} 167515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12248
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 502
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 52340
telemt_me_reconnect_success_total 11903
telemt_me_reader_eof_total 13501
telemt_me_idle_close_by_peer_total 13501
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 176143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 466410
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 38
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1232
telemt_desync_full_logged_total 320
telemt_desync_suppressed_total 912
telemt_desync_frames_bucket_total{bucket="1_2"} 336
telemt_desync_frames_bucket_total{bucket="3_10"} 502
telemt_desync_frames_bucket_total{bucket="gt_10"} 394
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 13283
telemt_me_refill_failed_total 1265
telemt_me_writer_restored_same_endpoint_total 11871
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1380
telemt_user_connections_total{user="hello"} 618341
telemt_user_connections_current{user="hello"} 919
telemt_user_octets_from_client{user="hello"} 11828564694 (11.02 GB)
telemt_user_octets_to_client{user="hello"} 207202330257 (192.97 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 60398.1 (16h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 819189
telemt_connections_bad_total 9425
telemt_handshake_timeouts_total 17465
telemt_upstream_connect_attempt_total 13289
telemt_upstream_connect_success_total 13217
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 13288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 13858
telemt_me_reconnect_success_total 10178
telemt_me_reader_eof_total 10878
telemt_me_idle_close_by_peer_total 10878
telemt_me_route_drop_no_conn_total 203426
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 670466
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2347
telemt_desync_full_logged_total 795
telemt_desync_suppressed_total 1552
telemt_desync_frames_bucket_total{bucket="1_2"} 710
telemt_desync_frames_bucket_total{bucket="3_10"} 904
telemt_desync_frames_bucket_total{bucket="gt_10"} 733
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10411
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 10170
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 233
telemt_user_connections_total{user="hello"} 670515
telemt_user_connections_current{user="hello"} 890
telemt_user_octets_from_client{user="hello"} 8440413968 (7.86 GB)
telemt_user_octets_to_client{user="hello"} 246467716676 (229.54 GB)
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 138
```