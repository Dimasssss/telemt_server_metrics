# Server Metrics 2026-03-11 19:11:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 103489.5 (28h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2629501
telemt_connections_bad_total 48650
telemt_handshake_timeouts_total 57604
telemt_upstream_connect_attempt_total 21797
telemt_upstream_connect_success_total 21785
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 21797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11015
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10660
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5329
telemt_me_reconnect_attempts_total 34449
telemt_me_reconnect_success_total 16562
telemt_me_reader_eof_total 17901
telemt_me_idle_close_by_peer_total 17901
telemt_me_route_drop_no_conn_total 991698
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2404193
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12199
telemt_desync_full_logged_total 3375
telemt_desync_suppressed_total 8824
telemt_desync_frames_bucket_total{bucket="1_2"} 2989
telemt_desync_frames_bucket_total{bucket="3_10"} 4715
telemt_desync_frames_bucket_total{bucket="gt_10"} 4495
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 17307
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 16556
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 745
telemt_user_connections_total{user="hello"} 2402543
telemt_user_connections_current{user="hello"} 1168
telemt_user_octets_from_client{user="hello"} 35786285048 (33.33 GB)
telemt_user_octets_to_client{user="hello"} 682357398384 (635.49 GB)
telemt_user_unique_ips_current{user="hello"} 330
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 103546.1 (28h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 980722
telemt_connections_bad_total 16429
telemt_handshake_timeouts_total 88146
telemt_upstream_connect_attempt_total 32012
telemt_upstream_connect_success_total 29043
telemt_upstream_connect_fail_total 2969
telemt_upstream_connect_attempts_per_request{bucket="1"} 32012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13084
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2048
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2969
telemt_me_keepalive_timeout_total 2848
telemt_me_reconnect_attempts_total 23006
telemt_me_reconnect_success_total 20891
telemt_me_reader_eof_total 22115
telemt_me_idle_close_by_peer_total 22112
telemt_me_route_drop_no_conn_total 370484
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 817982
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3235
telemt_desync_full_logged_total 1051
telemt_desync_suppressed_total 2184
telemt_desync_frames_bucket_total{bucket="1_2"} 1026
telemt_desync_frames_bucket_total{bucket="3_10"} 1153
telemt_desync_frames_bucket_total{bucket="gt_10"} 1056
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 21185
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 20868
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 294
telemt_user_connections_total{user="hello"} 820429
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 9845501710 (9.17 GB)
telemt_user_octets_to_client{user="hello"} 236995034312 (220.72 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 103546.0 (28h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1686745
telemt_connections_bad_total 10524
telemt_handshake_timeouts_total 133639
telemt_upstream_connect_attempt_total 26785
telemt_upstream_connect_success_total 26449
telemt_upstream_connect_fail_total 336
telemt_upstream_connect_attempts_per_request{bucket="1"} 26785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12035
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 336
telemt_me_keepalive_timeout_total 1984
telemt_me_reconnect_attempts_total 49803
telemt_me_reconnect_success_total 20148
telemt_me_reader_eof_total 21934
telemt_me_idle_close_by_peer_total 21934
telemt_me_route_drop_no_conn_total 615072
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1478730
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4098
telemt_desync_full_logged_total 1203
telemt_desync_suppressed_total 2895
telemt_desync_frames_bucket_total{bucket="1_2"} 954
telemt_desync_frames_bucket_total{bucket="3_10"} 1554
telemt_desync_frames_bucket_total{bucket="gt_10"} 1590
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 21354
telemt_me_refill_failed_total 921
telemt_me_writer_restored_same_endpoint_total 20136
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1206
telemt_user_connections_total{user="hello"} 1478397
telemt_user_connections_current{user="hello"} 681
telemt_user_octets_from_client{user="hello"} 19153426837 (17.84 GB)
telemt_user_octets_to_client{user="hello"} 450912529669 (419.95 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 103546.4 (28h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1205680
telemt_connections_bad_total 78200
telemt_handshake_timeouts_total 110507
telemt_upstream_connect_attempt_total 27992
telemt_upstream_connect_success_total 27992
telemt_upstream_connect_attempts_per_request{bucket="1"} 27992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12724
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1434
telemt_me_reconnect_attempts_total 27425
telemt_me_reconnect_success_total 22813
telemt_me_reader_eof_total 24204
telemt_me_idle_close_by_peer_total 24203
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 402604
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 982066
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2069
telemt_desync_full_logged_total 790
telemt_desync_suppressed_total 1279
telemt_desync_frames_bucket_total{bucket="1_2"} 757
telemt_desync_frames_bucket_total{bucket="3_10"} 704
telemt_desync_frames_bucket_total{bucket="gt_10"} 608
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 23197
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 22780
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 384
telemt_user_connections_total{user="hello"} 981326
telemt_user_connections_current{user="hello"} 506
telemt_user_octets_from_client{user="hello"} 11658906172 (10.86 GB)
telemt_user_octets_to_client{user="hello"} 297767087720 (277.32 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 8222.7 (2h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131309
telemt_connections_bad_total 640
telemt_handshake_timeouts_total 798
telemt_upstream_connect_attempt_total 2354
telemt_upstream_connect_success_total 2353
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1099
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 53
telemt_me_reconnect_attempts_total 1888
telemt_me_reconnect_success_total 1868
telemt_me_reader_eof_total 1904
telemt_me_idle_close_by_peer_total 1904
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 46176
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 120922
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 236
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 159
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1892
telemt_me_writer_restored_same_endpoint_total 1844
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 120890
telemt_user_connections_current{user="hello"} 645
telemt_user_octets_from_client{user="hello"} 6540327556 (6.09 GB)
telemt_user_octets_to_client{user="hello"} 41153478956 (38.33 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 79
```