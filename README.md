# Server Metrics 2026-03-12 21:54:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 57320.9 (15h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1892120
telemt_connections_bad_total 26057
telemt_handshake_timeouts_total 20760
telemt_upstream_connect_attempt_total 11238
telemt_upstream_connect_success_total 11173
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 11238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5318
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 595
telemt_me_reconnect_attempts_total 17142
telemt_me_reconnect_success_total 8289
telemt_me_reader_eof_total 8951
telemt_me_idle_close_by_peer_total 8950
telemt_me_route_drop_no_conn_total 740239
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1760952
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8468
telemt_desync_full_logged_total 2199
telemt_desync_suppressed_total 6269
telemt_desync_frames_bucket_total{bucket="1_2"} 2228
telemt_desync_frames_bucket_total{bucket="3_10"} 3051
telemt_desync_frames_bucket_total{bucket="gt_10"} 3189
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 8685
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 8276
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 396
telemt_user_connections_total{user="hello"} 1760432
telemt_user_connections_current{user="hello"} 731
telemt_user_octets_from_client{user="hello"} 26795045136 (24.95 GB)
telemt_user_octets_to_client{user="hello"} 622078602952 (579.36 GB)
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 86941.5 (24h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 786910
telemt_connections_bad_total 11689
telemt_handshake_timeouts_total 31123
telemt_upstream_connect_attempt_total 21963
telemt_upstream_connect_success_total 21934
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 21963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3403
telemt_me_reconnect_attempts_total 16036
telemt_me_reconnect_success_total 15943
telemt_me_reader_eof_total 16959
telemt_me_idle_close_by_peer_total 16959
telemt_me_route_drop_no_conn_total 254809
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 710341
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2991
telemt_desync_full_logged_total 928
telemt_desync_suppressed_total 2063
telemt_desync_frames_bucket_total{bucket="1_2"} 1182
telemt_desync_frames_bucket_total{bucket="3_10"} 982
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 16104
telemt_me_writer_restored_same_endpoint_total 15934
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 712221
telemt_user_connections_current{user="hello"} 291
telemt_user_octets_from_client{user="hello"} 12009064304 (11.18 GB)
telemt_user_octets_to_client{user="hello"} 272597656555 (253.88 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 86941.4 (24h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1630899
telemt_connections_bad_total 7736
telemt_handshake_timeouts_total 113031
telemt_upstream_connect_attempt_total 20325
telemt_upstream_connect_success_total 20319
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 20325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9360
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1214
telemt_me_reconnect_attempts_total 16865
telemt_me_reconnect_success_total 15617
telemt_me_reader_eof_total 16496
telemt_me_idle_close_by_peer_total 16495
telemt_me_route_drop_no_conn_total 537944
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1265326
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4954
telemt_desync_full_logged_total 1519
telemt_desync_suppressed_total 3435
telemt_desync_frames_bucket_total{bucket="1_2"} 790
telemt_desync_frames_bucket_total{bucket="3_10"} 1790
telemt_desync_frames_bucket_total{bucket="gt_10"} 2374
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 15763
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 15576
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 1264932
telemt_user_connections_current{user="hello"} 464
telemt_user_octets_from_client{user="hello"} 19619072816 (18.27 GB)
telemt_user_octets_to_client{user="hello"} 469911165561 (437.64 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 86941.8 (24h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1005999
telemt_connections_bad_total 12989
telemt_handshake_timeouts_total 71143
telemt_upstream_connect_attempt_total 22187
telemt_upstream_connect_success_total 22096
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 22187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12446
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9636
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 1681
telemt_me_reconnect_attempts_total 25485
telemt_me_reconnect_success_total 17756
telemt_me_reader_eof_total 18966
telemt_me_idle_close_by_peer_total 18966
telemt_me_route_drop_no_conn_total 360312
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 875539
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1852
telemt_desync_full_logged_total 613
telemt_desync_suppressed_total 1239
telemt_desync_frames_bucket_total{bucket="1_2"} 514
telemt_desync_frames_bucket_total{bucket="3_10"} 722
telemt_desync_frames_bucket_total{bucket="gt_10"} 616
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18138
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 17735
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 382
telemt_user_connections_total{user="hello"} 874888
telemt_user_connections_current{user="hello"} 282
telemt_user_octets_from_client{user="hello"} 14014183004 (13.05 GB)
telemt_user_octets_to_client{user="hello"} 351178652660 (327.06 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 86941.7 (24h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1124910
telemt_connections_bad_total 12532
telemt_handshake_timeouts_total 9094
telemt_upstream_connect_attempt_total 26707
telemt_upstream_connect_success_total 26379
telemt_upstream_connect_fail_total 328
telemt_upstream_connect_attempts_per_request{bucket="1"} 26707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12732
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 328
telemt_me_keepalive_timeout_total 1437
telemt_me_reconnect_attempts_total 33064
telemt_me_reconnect_success_total 22026
telemt_me_reader_eof_total 23158
telemt_me_idle_close_by_peer_total 23158
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 421487
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1034835
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3887
telemt_desync_full_logged_total 1353
telemt_desync_suppressed_total 2534
telemt_desync_frames_bucket_total{bucket="1_2"} 1143
telemt_desync_frames_bucket_total{bucket="3_10"} 1281
telemt_desync_frames_bucket_total{bucket="gt_10"} 1463
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 22624
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 21982
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 598
telemt_user_connections_total{user="hello"} 1034700
telemt_user_connections_current{user="hello"} 484
telemt_user_octets_from_client{user="hello"} 12771445080 (11.89 GB)
telemt_user_octets_to_client{user="hello"} 365703389876 (340.59 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 54
```