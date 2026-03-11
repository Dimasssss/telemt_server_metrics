# Server Metrics 2026-03-11 13:24:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 82655.6 (22h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1947315
telemt_connections_bad_total 27774
telemt_handshake_timeouts_total 50042
telemt_upstream_connect_attempt_total 17160
telemt_upstream_connect_success_total 17151
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 17160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8399
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 905
telemt_me_reconnect_attempts_total 25817
telemt_me_reconnect_success_total 12986
telemt_me_reader_eof_total 14022
telemt_me_idle_close_by_peer_total 14022
telemt_me_route_drop_no_conn_total 716579
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1778866
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9374
telemt_desync_full_logged_total 2535
telemt_desync_suppressed_total 6839
telemt_desync_frames_bucket_total{bucket="1_2"} 2322
telemt_desync_frames_bucket_total{bucket="3_10"} 3620
telemt_desync_frames_bucket_total{bucket="gt_10"} 3432
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 13524
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 12980
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 538
telemt_user_connections_total{user="hello"} 1777382
telemt_user_connections_current{user="hello"} 1494
telemt_user_octets_from_client{user="hello"} 23725324600 (22.10 GB)
telemt_user_octets_to_client{user="hello"} 505208693728 (470.51 GB)
telemt_user_unique_ips_current{user="hello"} 374
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 82712.3 (22h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 739222
telemt_connections_bad_total 13032
telemt_handshake_timeouts_total 51033
telemt_upstream_connect_attempt_total 26553
telemt_upstream_connect_success_total 23608
telemt_upstream_connect_fail_total 2945
telemt_upstream_connect_attempts_per_request{bucket="1"} 26553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10480
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2945
telemt_me_keepalive_timeout_total 2444
telemt_me_reconnect_attempts_total 17392
telemt_me_reconnect_success_total 16527
telemt_me_reader_eof_total 17494
telemt_me_idle_close_by_peer_total 17491
telemt_me_route_drop_no_conn_total 288928
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 622717
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2721
telemt_desync_full_logged_total 862
telemt_desync_suppressed_total 1859
telemt_desync_frames_bucket_total{bucket="1_2"} 854
telemt_desync_frames_bucket_total{bucket="3_10"} 991
telemt_desync_frames_bucket_total{bucket="gt_10"} 876
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 16737
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 16504
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 625203
telemt_user_connections_current{user="hello"} 639
telemt_user_octets_from_client{user="hello"} 6710353002 (6.25 GB)
telemt_user_octets_to_client{user="hello"} 178135511280 (165.90 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 82712.2 (22h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1271325
telemt_connections_bad_total 8303
telemt_handshake_timeouts_total 117192
telemt_upstream_connect_attempt_total 22023
telemt_upstream_connect_success_total 21756
telemt_upstream_connect_fail_total 267
telemt_upstream_connect_attempts_per_request{bucket="1"} 22023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9870
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 267
telemt_me_keepalive_timeout_total 890
telemt_me_reconnect_attempts_total 32633
telemt_me_reconnect_success_total 16530
telemt_me_reader_eof_total 17789
telemt_me_idle_close_by_peer_total 17789
telemt_me_route_drop_no_conn_total 440485
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1098302
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2949
telemt_desync_full_logged_total 877
telemt_desync_suppressed_total 2072
telemt_desync_frames_bucket_total{bucket="1_2"} 714
telemt_desync_frames_bucket_total{bucket="3_10"} 1110
telemt_desync_frames_bucket_total{bucket="gt_10"} 1125
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 17253
telemt_me_refill_failed_total 499
telemt_me_writer_restored_same_endpoint_total 16519
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 723
telemt_user_connections_total{user="hello"} 1098679
telemt_user_connections_current{user="hello"} 853
telemt_user_octets_from_client{user="hello"} 13032824873 (12.14 GB)
telemt_user_octets_to_client{user="hello"} 328954434373 (306.36 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 82712.6 (22h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 917822
telemt_connections_bad_total 77212
telemt_handshake_timeouts_total 87120
telemt_upstream_connect_attempt_total 22524
telemt_upstream_connect_success_total 22524
telemt_upstream_connect_attempts_per_request{bucket="1"} 22524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 923
telemt_me_reconnect_attempts_total 19473
telemt_me_reconnect_success_total 18404
telemt_me_reader_eof_total 19516
telemt_me_idle_close_by_peer_total 19515
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 294818
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 728215
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1545
telemt_desync_full_logged_total 608
telemt_desync_suppressed_total 937
telemt_desync_frames_bucket_total{bucket="1_2"} 560
telemt_desync_frames_bucket_total{bucket="3_10"} 547
telemt_desync_frames_bucket_total{bucket="gt_10"} 438
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 18630
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 18376
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 727580
telemt_user_connections_current{user="hello"} 544
telemt_user_octets_from_client{user="hello"} 8418048056 (7.84 GB)
telemt_user_octets_to_client{user="hello"} 211374706336 (196.86 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 82712.2 (22h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 999681
telemt_connections_bad_total 6814
telemt_handshake_timeouts_total 9232
telemt_upstream_connect_attempt_total 22576
telemt_upstream_connect_success_total 22479
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 22576
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10749
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 964
telemt_me_reconnect_attempts_total 22303
telemt_me_reconnect_success_total 18231
telemt_me_reader_eof_total 19221
telemt_me_idle_close_by_peer_total 19221
telemt_me_route_drop_no_conn_total 352977
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 907490
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3667
telemt_desync_full_logged_total 1350
telemt_desync_suppressed_total 2317
telemt_desync_frames_bucket_total{bucket="1_2"} 1291
telemt_desync_frames_bucket_total{bucket="3_10"} 1385
telemt_desync_frames_bucket_total{bucket="gt_10"} 991
telemt_pool_swap_total 55
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18592
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 18231
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 361
telemt_user_connections_total{user="hello"} 907233
telemt_user_connections_current{user="hello"} 700
telemt_user_octets_from_client{user="hello"} 13281487311 (12.37 GB)
telemt_user_octets_to_client{user="hello"} 324420260678 (302.14 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 99
```