# Server Metrics 2026-03-12 12:22:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 23011.7 (6h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 782949
telemt_connections_bad_total 1587
telemt_handshake_timeouts_total 5339
telemt_upstream_connect_attempt_total 4588
telemt_upstream_connect_success_total 4559
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 4588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2083
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 326
telemt_me_reconnect_attempts_total 7265
telemt_me_reconnect_success_total 3372
telemt_me_reader_eof_total 3614
telemt_me_idle_close_by_peer_total 3614
telemt_me_route_drop_no_conn_total 277190
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 754118
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3927
telemt_desync_full_logged_total 991
telemt_desync_suppressed_total 2936
telemt_desync_frames_bucket_total{bucket="1_2"} 994
telemt_desync_frames_bucket_total{bucket="3_10"} 1417
telemt_desync_frames_bucket_total{bucket="gt_10"} 1516
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3527
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3359
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 753960
telemt_user_connections_current{user="hello"} 1537
telemt_user_octets_from_client{user="hello"} 12998508052 (12.11 GB)
telemt_user_octets_to_client{user="hello"} 210533151160 (196.07 GB)
telemt_user_unique_ips_current{user="hello"} 407
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 52632.3 (14h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 399194
telemt_connections_bad_total 4882
telemt_handshake_timeouts_total 21114
telemt_upstream_connect_attempt_total 12818
telemt_upstream_connect_success_total 12811
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 12818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6481
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1054
telemt_me_reconnect_attempts_total 10052
telemt_me_reconnect_success_total 9995
telemt_me_reader_eof_total 10627
telemt_me_idle_close_by_peer_total 10627
telemt_me_route_drop_no_conn_total 114426
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 351591
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1140
telemt_desync_full_logged_total 374
telemt_desync_suppressed_total 766
telemt_desync_frames_bucket_total{bucket="1_2"} 444
telemt_desync_frames_bucket_total{bucket="3_10"} 392
telemt_desync_frames_bucket_total{bucket="gt_10"} 304
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 10087
telemt_me_writer_restored_same_endpoint_total 9986
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 352055
telemt_user_connections_current{user="hello"} 543
telemt_user_octets_from_client{user="hello"} 4754391883 (4.43 GB)
telemt_user_octets_to_client{user="hello"} 125674108722 (117.04 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 52632.1 (14h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 905277
telemt_connections_bad_total 5046
telemt_handshake_timeouts_total 67800
telemt_upstream_connect_attempt_total 12925
telemt_upstream_connect_success_total 12920
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 12925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5805
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 859
telemt_me_reconnect_attempts_total 10016
telemt_me_reconnect_success_total 9932
telemt_me_reader_eof_total 10453
telemt_me_idle_close_by_peer_total 10453
telemt_me_route_drop_no_conn_total 220538
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 616347
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2846
telemt_desync_full_logged_total 847
telemt_desync_suppressed_total 1999
telemt_desync_frames_bucket_total{bucket="1_2"} 406
telemt_desync_frames_bucket_total{bucket="3_10"} 1002
telemt_desync_frames_bucket_total{bucket="gt_10"} 1438
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 9955
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 9891
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 616581
telemt_user_connections_current{user="hello"} 916
telemt_user_octets_from_client{user="hello"} 8072279916 (7.52 GB)
telemt_user_octets_to_client{user="hello"} 194625607777 (181.26 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 52632.7 (14h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 505618
telemt_connections_bad_total 7629
telemt_handshake_timeouts_total 46982
telemt_upstream_connect_attempt_total 14165
telemt_upstream_connect_success_total 14109
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 14165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8022
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6075
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 1266
telemt_me_reconnect_attempts_total 12702
telemt_me_reconnect_success_total 11471
telemt_me_reader_eof_total 12167
telemt_me_idle_close_by_peer_total 12167
telemt_me_route_drop_no_conn_total 165580
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 420875
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 846
telemt_desync_full_logged_total 295
telemt_desync_suppressed_total 551
telemt_desync_frames_bucket_total{bucket="1_2"} 248
telemt_desync_frames_bucket_total{bucket="3_10"} 355
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11594
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11450
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 420698
telemt_user_connections_current{user="hello"} 690
telemt_user_octets_from_client{user="hello"} 4790829612 (4.46 GB)
telemt_user_octets_to_client{user="hello"} 162782846620 (151.60 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 52632.5 (14h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 567688
telemt_connections_bad_total 1695
telemt_handshake_timeouts_total 4477
telemt_upstream_connect_attempt_total 17115
telemt_upstream_connect_success_total 16911
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 17115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8182
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_timeout_total 962
telemt_me_reconnect_attempts_total 20210
telemt_me_reconnect_success_total 14267
telemt_me_reader_eof_total 14927
telemt_me_idle_close_by_peer_total 14927
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 189542
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 530439
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2223
telemt_desync_full_logged_total 747
telemt_desync_suppressed_total 1476
telemt_desync_frames_bucket_total{bucket="1_2"} 639
telemt_desync_frames_bucket_total{bucket="3_10"} 783
telemt_desync_frames_bucket_total{bucket="gt_10"} 801
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 14591
telemt_me_refill_failed_total 184
telemt_me_writer_restored_same_endpoint_total 14240
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 530353
telemt_user_connections_current{user="hello"} 828
telemt_user_octets_from_client{user="hello"} 6177171044 (5.75 GB)
telemt_user_octets_to_client{user="hello"} 134409225264 (125.18 GB)
telemt_user_unique_ips_current{user="hello"} 218
telemt_user_unique_ips_recent_window{user="hello"} 125
```