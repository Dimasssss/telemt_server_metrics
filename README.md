# Server Metrics 2026-03-12 15:30:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 34339.3 (9h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1234937
telemt_connections_bad_total 20234
telemt_handshake_timeouts_total 12346
telemt_upstream_connect_attempt_total 6934
telemt_upstream_connect_success_total 6897
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 6934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3190
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 416
telemt_me_reconnect_attempts_total 9034
telemt_me_reconnect_success_total 5128
telemt_me_reader_eof_total 5460
telemt_me_idle_close_by_peer_total 5459
telemt_me_route_drop_no_conn_total 440088
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1162151
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6189
telemt_desync_full_logged_total 1542
telemt_desync_suppressed_total 4647
telemt_desync_frames_bucket_total{bucket="1_2"} 1594
telemt_desync_frames_bucket_total{bucket="3_10"} 2219
telemt_desync_frames_bucket_total{bucket="gt_10"} 2376
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 5312
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 5115
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 1161833
telemt_user_connections_current{user="hello"} 1536
telemt_user_octets_from_client{user="hello"} 18167258392 (16.92 GB)
telemt_user_octets_to_client{user="hello"} 338087811480 (314.87 GB)
telemt_user_unique_ips_current{user="hello"} 440
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 63959.8 (17h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 556902
telemt_connections_bad_total 6753
telemt_handshake_timeouts_total 27335
telemt_upstream_connect_attempt_total 15392
telemt_upstream_connect_success_total 15385
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 15392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7717
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1179
telemt_me_reconnect_attempts_total 12068
telemt_me_reconnect_success_total 12001
telemt_me_reader_eof_total 12746
telemt_me_idle_close_by_peer_total 12746
telemt_me_route_drop_no_conn_total 163924
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 497037
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1912
telemt_desync_full_logged_total 604
telemt_desync_suppressed_total 1308
telemt_desync_frames_bucket_total{bucket="1_2"} 838
telemt_desync_frames_bucket_total{bucket="3_10"} 615
telemt_desync_frames_bucket_total{bucket="gt_10"} 459
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 12118
telemt_me_writer_restored_same_endpoint_total 11992
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 497535
telemt_user_connections_current{user="hello"} 648
telemt_user_octets_from_client{user="hello"} 7730453539 (7.20 GB)
telemt_user_octets_to_client{user="hello"} 176414729246 (164.30 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 63959.7 (17h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1187001
telemt_connections_bad_total 6162
telemt_handshake_timeouts_total 82820
telemt_upstream_connect_attempt_total 15427
telemt_upstream_connect_success_total 15422
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 15427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7025
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 989
telemt_me_reconnect_attempts_total 13089
telemt_me_reconnect_success_total 11866
telemt_me_reader_eof_total 12504
telemt_me_idle_close_by_peer_total 12504
telemt_me_route_drop_no_conn_total 319203
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 873453
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3651
telemt_desync_full_logged_total 1124
telemt_desync_suppressed_total 2527
telemt_desync_frames_bucket_total{bucket="1_2"} 553
telemt_desync_frames_bucket_total{bucket="3_10"} 1323
telemt_desync_frames_bucket_total{bucket="gt_10"} 1775
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 11952
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 11825
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 873639
telemt_user_connections_current{user="hello"} 992
telemt_user_octets_from_client{user="hello"} 11599700220 (10.80 GB)
telemt_user_octets_to_client{user="hello"} 274016733201 (255.20 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 63960.3 (17h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 703292
telemt_connections_bad_total 7701
telemt_handshake_timeouts_total 57882
telemt_upstream_connect_attempt_total 16886
telemt_upstream_connect_success_total 16817
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 16886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7255
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 1368
telemt_me_reconnect_attempts_total 18861
telemt_me_reconnect_success_total 13623
telemt_me_reader_eof_total 14524
telemt_me_idle_close_by_peer_total 14524
telemt_me_route_drop_no_conn_total 239152
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 603689
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1214
telemt_desync_full_logged_total 418
telemt_desync_suppressed_total 796
telemt_desync_frames_bucket_total{bucket="1_2"} 329
telemt_desync_frames_bucket_total{bucket="3_10"} 486
telemt_desync_frames_bucket_total{bucket="gt_10"} 399
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 13890
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 13602
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 603176
telemt_user_connections_current{user="hello"} 585
telemt_user_octets_from_client{user="hello"} 7330520044 (6.83 GB)
telemt_user_octets_to_client{user="hello"} 238693014256 (222.30 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 63960.2 (17h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 792253
telemt_connections_bad_total 7723
telemt_handshake_timeouts_total 6246
telemt_upstream_connect_attempt_total 20311
telemt_upstream_connect_success_total 20062
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 20311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9771
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_keepalive_timeout_total 1120
telemt_me_reconnect_attempts_total 24103
telemt_me_reconnect_success_total 16866
telemt_me_reader_eof_total 17639
telemt_me_idle_close_by_peer_total 17639
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 276540
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 731631
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2890
telemt_desync_full_logged_total 980
telemt_desync_suppressed_total 1910
telemt_desync_frames_bucket_total{bucket="1_2"} 820
telemt_desync_frames_bucket_total{bucket="3_10"} 987
telemt_desync_frames_bucket_total{bucket="gt_10"} 1083
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 17267
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 16832
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 401
telemt_user_connections_total{user="hello"} 731531
telemt_user_connections_current{user="hello"} 918
telemt_user_octets_from_client{user="hello"} 8741709404 (8.14 GB)
telemt_user_octets_to_client{user="hello"} 205636312600 (191.51 GB)
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 137
```