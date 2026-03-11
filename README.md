# Server Metrics 2026-03-11 15:06:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 88784.5 (24h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2165955
telemt_connections_bad_total 34692
telemt_handshake_timeouts_total 52346
telemt_upstream_connect_attempt_total 18693
telemt_upstream_connect_success_total 18681
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 18693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9183
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 4879
telemt_me_reconnect_attempts_total 32052
telemt_me_reconnect_success_total 14186
telemt_me_reader_eof_total 15400
telemt_me_idle_close_by_peer_total 15400
telemt_me_route_drop_no_conn_total 801949
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1982768
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10393
telemt_desync_full_logged_total 2821
telemt_desync_suppressed_total 7572
telemt_desync_frames_bucket_total{bucket="1_2"} 2584
telemt_desync_frames_bucket_total{bucket="3_10"} 3999
telemt_desync_frames_bucket_total{bucket="gt_10"} 3810
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 14899
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 14180
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 713
telemt_user_connections_total{user="hello"} 1981243
telemt_user_connections_current{user="hello"} 1273
telemt_user_octets_from_client{user="hello"} 26633658724 (24.80 GB)
telemt_user_octets_to_client{user="hello"} 564146349480 (525.40 GB)
telemt_user_unique_ips_current{user="hello"} 379
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 88841.3 (24h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 806679
telemt_connections_bad_total 13251
telemt_handshake_timeouts_total 54800
telemt_upstream_connect_attempt_total 28158
telemt_upstream_connect_success_total 25205
telemt_upstream_connect_fail_total 2953
telemt_upstream_connect_attempts_per_request{bucket="1"} 28158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11682
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11275
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2953
telemt_me_keepalive_timeout_total 2541
telemt_me_reconnect_attempts_total 19897
telemt_me_reconnect_success_total 17805
telemt_me_reader_eof_total 18864
telemt_me_idle_close_by_peer_total 18861
telemt_me_route_drop_no_conn_total 316713
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 684749
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2873
telemt_desync_full_logged_total 914
telemt_desync_suppressed_total 1959
telemt_desync_frames_bucket_total{bucket="1_2"} 890
telemt_desync_frames_bucket_total{bucket="3_10"} 1036
telemt_desync_frames_bucket_total{bucket="gt_10"} 947
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18067
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 17782
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 262
telemt_user_connections_total{user="hello"} 687225
telemt_user_connections_current{user="hello"} 501
telemt_user_octets_from_client{user="hello"} 7863248970 (7.32 GB)
telemt_user_octets_to_client{user="hello"} 194172784680 (180.84 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 88841.1 (24h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1401385
telemt_connections_bad_total 8556
telemt_handshake_timeouts_total 123470
telemt_upstream_connect_attempt_total 23548
telemt_upstream_connect_success_total 23266
telemt_upstream_connect_fail_total 282
telemt_upstream_connect_attempts_per_request{bucket="1"} 23548
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10582
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 282
telemt_me_keepalive_timeout_total 1582
telemt_me_reconnect_attempts_total 34724
telemt_me_reconnect_success_total 17713
telemt_me_reader_eof_total 19046
telemt_me_idle_close_by_peer_total 19046
telemt_me_route_drop_no_conn_total 508935
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1217764
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3234
telemt_desync_full_logged_total 956
telemt_desync_suppressed_total 2278
telemt_desync_frames_bucket_total{bucket="1_2"} 794
telemt_desync_frames_bucket_total{bucket="3_10"} 1224
telemt_desync_frames_bucket_total{bucket="gt_10"} 1216
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 18486
telemt_me_refill_failed_total 527
telemt_me_writer_restored_same_endpoint_total 17702
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 773
telemt_user_connections_total{user="hello"} 1217516
telemt_user_connections_current{user="hello"} 816
telemt_user_octets_from_client{user="hello"} 14602537513 (13.60 GB)
telemt_user_octets_to_client{user="hello"} 364433552113 (339.41 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 88841.7 (24h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1004416
telemt_connections_bad_total 77737
telemt_handshake_timeouts_total 96849
telemt_upstream_connect_attempt_total 23827
telemt_upstream_connect_success_total 23827
telemt_upstream_connect_attempts_per_request{bucket="1"} 23827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10782
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 994
telemt_me_reconnect_attempts_total 20472
telemt_me_reconnect_success_total 19398
telemt_me_reader_eof_total 20577
telemt_me_idle_close_by_peer_total 20576
telemt_me_seq_mismatch_total 18
telemt_me_route_drop_no_conn_total 328096
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 802469
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 29
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1693
telemt_desync_full_logged_total 653
telemt_desync_suppressed_total 1040
telemt_desync_frames_bucket_total{bucket="1_2"} 605
telemt_desync_frames_bucket_total{bucket="3_10"} 600
telemt_desync_frames_bucket_total{bucket="gt_10"} 488
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 19637
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 19369
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 239
telemt_user_connections_total{user="hello"} 801793
telemt_user_connections_current{user="hello"} 562
telemt_user_octets_from_client{user="hello"} 9389642068 (8.74 GB)
telemt_user_octets_to_client{user="hello"} 235685958516 (219.50 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 88841.1 (24h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1106967
telemt_connections_bad_total 6936
telemt_handshake_timeouts_total 11222
telemt_upstream_connect_attempt_total 24081
telemt_upstream_connect_success_total 23975
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 24081
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11529
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 195
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 1940
telemt_me_reconnect_attempts_total 23491
telemt_me_reconnect_success_total 19405
telemt_me_reader_eof_total 20458
telemt_me_idle_close_by_peer_total 20458
telemt_me_route_drop_no_conn_total 394240
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1006126
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3870
telemt_desync_full_logged_total 1417
telemt_desync_suppressed_total 2453
telemt_desync_frames_bucket_total{bucket="1_2"} 1340
telemt_desync_frames_bucket_total{bucket="3_10"} 1455
telemt_desync_frames_bucket_total{bucket="gt_10"} 1075
telemt_pool_swap_total 59
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19784
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 19405
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 379
telemt_user_connections_total{user="hello"} 1005842
telemt_user_connections_current{user="hello"} 700
telemt_user_octets_from_client{user="hello"} 14392180899 (13.40 GB)
telemt_user_octets_to_client{user="hello"} 353214806486 (328.96 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 107
```