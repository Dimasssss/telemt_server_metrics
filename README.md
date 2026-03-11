# Server Metrics 2026-03-11 15:11:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 89091.4 (24h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2176465
telemt_connections_bad_total 35090
telemt_handshake_timeouts_total 52409
telemt_upstream_connect_attempt_total 18714
telemt_upstream_connect_success_total 18702
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 18714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9200
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 4890
telemt_me_reconnect_attempts_total 32073
telemt_me_reconnect_success_total 14207
telemt_me_reader_eof_total 15421
telemt_me_idle_close_by_peer_total 15421
telemt_me_route_drop_no_conn_total 806197
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1992332
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10435
telemt_desync_full_logged_total 2833
telemt_desync_suppressed_total 7602
telemt_desync_frames_bucket_total{bucket="1_2"} 2592
telemt_desync_frames_bucket_total{bucket="3_10"} 4017
telemt_desync_frames_bucket_total{bucket="gt_10"} 3826
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 14920
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 14201
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 713
telemt_user_connections_total{user="hello"} 1990802
telemt_user_connections_current{user="hello"} 1330
telemt_user_octets_from_client{user="hello"} 26717077776 (24.88 GB)
telemt_user_octets_to_client{user="hello"} 566286512720 (527.40 GB)
telemt_user_unique_ips_current{user="hello"} 374
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 89148.0 (24h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 810117
telemt_connections_bad_total 13251
telemt_handshake_timeouts_total 54913
telemt_upstream_connect_attempt_total 28208
telemt_upstream_connect_success_total 25252
telemt_upstream_connect_fail_total 2956
telemt_upstream_connect_attempts_per_request{bucket="1"} 28208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11705
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11299
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2956
telemt_me_keepalive_timeout_total 2549
telemt_me_reconnect_attempts_total 19933
telemt_me_reconnect_success_total 17841
telemt_me_reader_eof_total 18900
telemt_me_idle_close_by_peer_total 18897
telemt_me_route_drop_no_conn_total 317740
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 688016
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2883
telemt_desync_full_logged_total 915
telemt_desync_suppressed_total 1968
telemt_desync_frames_bucket_total{bucket="1_2"} 891
telemt_desync_frames_bucket_total{bucket="3_10"} 1040
telemt_desync_frames_bucket_total{bucket="gt_10"} 952
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18103
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 17818
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 262
telemt_user_connections_total{user="hello"} 690492
telemt_user_connections_current{user="hello"} 572
telemt_user_octets_from_client{user="hello"} 7946631378 (7.40 GB)
telemt_user_octets_to_client{user="hello"} 194950253628 (181.56 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 89147.9 (24h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1407392
telemt_connections_bad_total 8647
telemt_handshake_timeouts_total 123609
telemt_upstream_connect_attempt_total 23599
telemt_upstream_connect_success_total 23317
telemt_upstream_connect_fail_total 282
telemt_upstream_connect_attempts_per_request{bucket="1"} 23599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10604
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 282
telemt_me_keepalive_timeout_total 1586
telemt_me_reconnect_attempts_total 34763
telemt_me_reconnect_success_total 17752
telemt_me_reader_eof_total 19086
telemt_me_idle_close_by_peer_total 19086
telemt_me_route_drop_no_conn_total 511369
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1223457
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3247
telemt_desync_full_logged_total 961
telemt_desync_suppressed_total 2286
telemt_desync_frames_bucket_total{bucket="1_2"} 799
telemt_desync_frames_bucket_total{bucket="3_10"} 1228
telemt_desync_frames_bucket_total{bucket="gt_10"} 1220
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 18526
telemt_me_refill_failed_total 527
telemt_me_writer_restored_same_endpoint_total 17741
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 774
telemt_user_connections_total{user="hello"} 1223209
telemt_user_connections_current{user="hello"} 793
telemt_user_octets_from_client{user="hello"} 14707384665 (13.70 GB)
telemt_user_octets_to_client{user="hello"} 366174852453 (341.03 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 89148.4 (24h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1008332
telemt_connections_bad_total 77737
telemt_handshake_timeouts_total 97068
telemt_upstream_connect_attempt_total 23855
telemt_upstream_connect_success_total 23855
telemt_upstream_connect_attempts_per_request{bucket="1"} 23855
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10791
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1005
telemt_me_reconnect_attempts_total 20497
telemt_me_reconnect_success_total 19423
telemt_me_reader_eof_total 20602
telemt_me_idle_close_by_peer_total 20601
telemt_me_seq_mismatch_total 18
telemt_me_route_drop_no_conn_total 329551
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 805791
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 29
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1696
telemt_desync_full_logged_total 655
telemt_desync_suppressed_total 1041
telemt_desync_frames_bucket_total{bucket="1_2"} 606
telemt_desync_frames_bucket_total{bucket="3_10"} 602
telemt_desync_frames_bucket_total{bucket="gt_10"} 488
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 19662
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 19394
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 239
telemt_user_connections_total{user="hello"} 805115
telemt_user_connections_current{user="hello"} 546
telemt_user_octets_from_client{user="hello"} 9424774068 (8.78 GB)
telemt_user_octets_to_client{user="hello"} 237373267504 (221.07 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 89148.4 (24h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1113334
telemt_connections_bad_total 6936
telemt_handshake_timeouts_total 11247
telemt_upstream_connect_attempt_total 24154
telemt_upstream_connect_success_total 24048
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 24154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11574
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 196
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 1948
telemt_me_reconnect_attempts_total 23551
telemt_me_reconnect_success_total 19465
telemt_me_reader_eof_total 20519
telemt_me_idle_close_by_peer_total 20519
telemt_me_route_drop_no_conn_total 396296
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1011955
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3897
telemt_desync_full_logged_total 1425
telemt_desync_suppressed_total 2472
telemt_desync_frames_bucket_total{bucket="1_2"} 1345
telemt_desync_frames_bucket_total{bucket="3_10"} 1460
telemt_desync_frames_bucket_total{bucket="gt_10"} 1092
telemt_pool_swap_total 59
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19845
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 19465
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 380
telemt_user_connections_total{user="hello"} 1011669
telemt_user_connections_current{user="hello"} 853
telemt_user_octets_from_client{user="hello"} 14425705331 (13.43 GB)
telemt_user_octets_to_client{user="hello"} 354520934942 (330.17 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 107
```