# Server Metrics 2026-03-12 16:42:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 38629.3 (10h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1396610
telemt_connections_bad_total 20252
telemt_handshake_timeouts_total 13312
telemt_upstream_connect_attempt_total 7765
telemt_upstream_connect_success_total 7722
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 7765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3636
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 469
telemt_me_reconnect_attempts_total 10740
telemt_me_reconnect_success_total 5770
telemt_me_reader_eof_total 6160
telemt_me_idle_close_by_peer_total 6159
telemt_me_route_drop_no_conn_total 508511
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1309216
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6730
telemt_desync_full_logged_total 1689
telemt_desync_suppressed_total 5041
telemt_desync_frames_bucket_total{bucket="1_2"} 1734
telemt_desync_frames_bucket_total{bucket="3_10"} 2434
telemt_desync_frames_bucket_total{bucket="gt_10"} 2562
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6000
telemt_me_refill_failed_total 154
telemt_me_writer_restored_same_endpoint_total 5757
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 230
telemt_user_connections_total{user="hello"} 1308888
telemt_user_connections_current{user="hello"} 1758
telemt_user_octets_from_client{user="hello"} 19985756560 (18.61 GB)
telemt_user_octets_to_client{user="hello"} 378680095416 (352.67 GB)
telemt_user_unique_ips_current{user="hello"} 465
telemt_user_unique_ips_recent_window{user="hello"} 279
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 68249.7 (18h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 613101
telemt_connections_bad_total 8028
telemt_handshake_timeouts_total 28614
telemt_upstream_connect_attempt_total 16306
telemt_upstream_connect_success_total 16299
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 16306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8162
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1276
telemt_me_reconnect_attempts_total 12789
telemt_me_reconnect_success_total 12716
telemt_me_reader_eof_total 13506
telemt_me_idle_close_by_peer_total 13506
telemt_me_route_drop_no_conn_total 186672
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 549377
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2195
telemt_desync_full_logged_total 695
telemt_desync_suppressed_total 1500
telemt_desync_frames_bucket_total{bucket="1_2"} 970
telemt_desync_frames_bucket_total{bucket="3_10"} 701
telemt_desync_frames_bucket_total{bucket="gt_10"} 524
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 12843
telemt_me_writer_restored_same_endpoint_total 12707
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 549895
telemt_user_connections_current{user="hello"} 674
telemt_user_octets_from_client{user="hello"} 8459763927 (7.88 GB)
telemt_user_octets_to_client{user="hello"} 193575524454 (180.28 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 68249.7 (18h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1289970
telemt_connections_bad_total 6410
telemt_handshake_timeouts_total 94244
telemt_upstream_connect_attempt_total 16283
telemt_upstream_connect_success_total 16278
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 16283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7427
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1080
telemt_me_reconnect_attempts_total 13747
telemt_me_reconnect_success_total 12515
telemt_me_reader_eof_total 13200
telemt_me_idle_close_by_peer_total 13199
telemt_me_route_drop_no_conn_total 359207
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 962242
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4116
telemt_desync_full_logged_total 1264
telemt_desync_suppressed_total 2852
telemt_desync_frames_bucket_total{bucket="1_2"} 642
telemt_desync_frames_bucket_total{bucket="3_10"} 1483
telemt_desync_frames_bucket_total{bucket="gt_10"} 1991
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 12609
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 12474
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 962400
telemt_user_connections_current{user="hello"} 1107
telemt_user_octets_from_client{user="hello"} 12466886508 (11.61 GB)
telemt_user_octets_to_client{user="hello"} 303596984285 (282.75 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 68250.3 (18h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 773992
telemt_connections_bad_total 7730
telemt_handshake_timeouts_total 61040
telemt_upstream_connect_attempt_total 17841
telemt_upstream_connect_success_total 17769
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 17840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7700
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 1515
telemt_me_reconnect_attempts_total 19612
telemt_me_reconnect_success_total 14363
telemt_me_reader_eof_total 15306
telemt_me_idle_close_by_peer_total 15306
telemt_me_route_drop_no_conn_total 266831
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 669378
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1370
telemt_desync_full_logged_total 462
telemt_desync_suppressed_total 908
telemt_desync_frames_bucket_total{bucket="1_2"} 378
telemt_desync_frames_bucket_total{bucket="3_10"} 540
telemt_desync_frames_bucket_total{bucket="gt_10"} 452
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 14636
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 14342
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 273
telemt_user_connections_total{user="hello"} 668816
telemt_user_connections_current{user="hello"} 714
telemt_user_octets_from_client{user="hello"} 8275762568 (7.71 GB)
telemt_user_octets_to_client{user="hello"} 259128570728 (241.33 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 68249.9 (18h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 874067
telemt_connections_bad_total 11231
telemt_handshake_timeouts_total 7158
telemt_upstream_connect_attempt_total 21489
telemt_upstream_connect_success_total 21228
telemt_upstream_connect_fail_total 261
telemt_upstream_connect_attempts_per_request{bucket="1"} 21489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10276
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 261
telemt_me_keepalive_timeout_total 1227
telemt_me_reconnect_attempts_total 25061
telemt_me_reconnect_success_total 17818
telemt_me_reader_eof_total 18640
telemt_me_idle_close_by_peer_total 18640
telemt_me_seq_mismatch_total 32
telemt_me_route_drop_no_conn_total 311793
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 802949
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3155
telemt_desync_full_logged_total 1071
telemt_desync_suppressed_total 2084
telemt_desync_frames_bucket_total{bucket="1_2"} 861
telemt_desync_frames_bucket_total{bucket="3_10"} 1077
telemt_desync_frames_bucket_total{bucket="gt_10"} 1217
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 18234
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 17775
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 416
telemt_user_connections_total{user="hello"} 802838
telemt_user_connections_current{user="hello"} 991
telemt_user_octets_from_client{user="hello"} 9924457356 (9.24 GB)
telemt_user_octets_to_client{user="hello"} 227944161404 (212.29 GB)
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 167
```