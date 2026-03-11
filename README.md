# Server Metrics 2026-03-11 14:46:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 87559.1 (24h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2125466
telemt_connections_bad_total 34611
telemt_handshake_timeouts_total 52205
telemt_upstream_connect_attempt_total 18516
telemt_upstream_connect_success_total 18504
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 18516
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9085
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 4849
telemt_me_reconnect_attempts_total 30610
telemt_me_reconnect_success_total 14056
telemt_me_reader_eof_total 15225
telemt_me_idle_close_by_peer_total 15225
telemt_me_route_drop_no_conn_total 785264
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1943319
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10160
telemt_desync_full_logged_total 2756
telemt_desync_suppressed_total 7404
telemt_desync_frames_bucket_total{bucket="1_2"} 2529
telemt_desync_frames_bucket_total{bucket="3_10"} 3913
telemt_desync_frames_bucket_total{bucket="gt_10"} 3718
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 14724
telemt_me_refill_failed_total 514
telemt_me_writer_restored_same_endpoint_total 14050
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 668
telemt_user_connections_total{user="hello"} 1941816
telemt_user_connections_current{user="hello"} 1472
telemt_user_octets_from_client{user="hello"} 26155843412 (24.36 GB)
telemt_user_octets_to_client{user="hello"} 555066619372 (516.95 GB)
telemt_user_unique_ips_current{user="hello"} 387
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 87615.9 (24h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 794066
telemt_connections_bad_total 13232
telemt_handshake_timeouts_total 54072
telemt_upstream_connect_attempt_total 27935
telemt_upstream_connect_success_total 24984
telemt_upstream_connect_fail_total 2951
telemt_upstream_connect_attempts_per_request{bucket="1"} 27935
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11163
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2951
telemt_me_keepalive_timeout_total 2524
telemt_me_reconnect_attempts_total 19719
telemt_me_reconnect_success_total 17628
telemt_me_reader_eof_total 18677
telemt_me_idle_close_by_peer_total 18674
telemt_me_route_drop_no_conn_total 311560
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 673121
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2848
telemt_desync_full_logged_total 906
telemt_desync_suppressed_total 1942
telemt_desync_frames_bucket_total{bucket="1_2"} 882
telemt_desync_frames_bucket_total{bucket="3_10"} 1031
telemt_desync_frames_bucket_total{bucket="gt_10"} 935
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 17889
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 17605
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 261
telemt_user_connections_total{user="hello"} 675598
telemt_user_connections_current{user="hello"} 541
telemt_user_octets_from_client{user="hello"} 7727814994 (7.20 GB)
telemt_user_octets_to_client{user="hello"} 190864327864 (177.76 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 87615.9 (24h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1376741
telemt_connections_bad_total 8455
telemt_handshake_timeouts_total 122314
telemt_upstream_connect_attempt_total 23283
telemt_upstream_connect_success_total 23004
telemt_upstream_connect_fail_total 279
telemt_upstream_connect_attempts_per_request{bucket="1"} 23283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10478
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 279
telemt_me_keepalive_timeout_total 1565
telemt_me_reconnect_attempts_total 33612
telemt_me_reconnect_success_total 17500
telemt_me_reader_eof_total 18801
telemt_me_idle_close_by_peer_total 18801
telemt_me_route_drop_no_conn_total 498682
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1194948
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3171
telemt_desync_full_logged_total 937
telemt_desync_suppressed_total 2234
telemt_desync_frames_bucket_total{bucket="1_2"} 775
telemt_desync_frames_bucket_total{bucket="3_10"} 1199
telemt_desync_frames_bucket_total{bucket="gt_10"} 1197
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 18242
telemt_me_refill_failed_total 499
telemt_me_writer_restored_same_endpoint_total 17489
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 742
telemt_user_connections_total{user="hello"} 1194717
telemt_user_connections_current{user="hello"} 814
telemt_user_octets_from_client{user="hello"} 14321630325 (13.34 GB)
telemt_user_octets_to_client{user="hello"} 357553466317 (333.00 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 87616.2 (24h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 987152
telemt_connections_bad_total 77575
telemt_handshake_timeouts_total 94265
telemt_upstream_connect_attempt_total 23616
telemt_upstream_connect_success_total 23616
telemt_upstream_connect_attempts_per_request{bucket="1"} 23616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10692
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 964
telemt_me_reconnect_attempts_total 20304
telemt_me_reconnect_success_total 19231
telemt_me_reader_eof_total 20400
telemt_me_idle_close_by_peer_total 20399
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 321662
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 788510
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1679
telemt_desync_full_logged_total 648
telemt_desync_suppressed_total 1031
telemt_desync_frames_bucket_total{bucket="1_2"} 601
telemt_desync_frames_bucket_total{bucket="3_10"} 596
telemt_desync_frames_bucket_total{bucket="gt_10"} 482
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 19468
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 19203
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 237
telemt_user_connections_total{user="hello"} 787836
telemt_user_connections_current{user="hello"} 614
telemt_user_octets_from_client{user="hello"} 9209329088 (8.58 GB)
telemt_user_octets_to_client{user="hello"} 230833267004 (214.98 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 87615.8 (24h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1087091
telemt_connections_bad_total 6936
telemt_handshake_timeouts_total 11026
telemt_upstream_connect_attempt_total 23794
telemt_upstream_connect_success_total 23688
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 23794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11383
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 1907
telemt_me_reconnect_attempts_total 23251
telemt_me_reconnect_success_total 19166
telemt_me_reader_eof_total 20215
telemt_me_idle_close_by_peer_total 20215
telemt_me_route_drop_no_conn_total 385964
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 987679
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3825
telemt_desync_full_logged_total 1402
telemt_desync_suppressed_total 2423
telemt_desync_frames_bucket_total{bucket="1_2"} 1336
telemt_desync_frames_bucket_total{bucket="3_10"} 1439
telemt_desync_frames_bucket_total{bucket="gt_10"} 1050
telemt_pool_swap_total 59
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19541
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 19166
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 375
telemt_user_connections_total{user="hello"} 987405
telemt_user_connections_current{user="hello"} 668
telemt_user_octets_from_client{user="hello"} 14222207899 (13.25 GB)
telemt_user_octets_to_client{user="hello"} 346311619138 (322.53 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 101
```