# Server Metrics 2026-03-11 18:36:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 101347.2 (28h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2570724
telemt_connections_bad_total 48538
telemt_handshake_timeouts_total 56625
telemt_upstream_connect_attempt_total 21398
telemt_upstream_connect_success_total 21386
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 21398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10810
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10471
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5314
telemt_me_reconnect_attempts_total 34138
telemt_me_reconnect_success_total 16257
telemt_me_reader_eof_total 17585
telemt_me_idle_close_by_peer_total 17585
telemt_me_route_drop_no_conn_total 961810
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2351637
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11944
telemt_desync_full_logged_total 3299
telemt_desync_suppressed_total 8645
telemt_desync_frames_bucket_total{bucket="1_2"} 2939
telemt_desync_frames_bucket_total{bucket="3_10"} 4614
telemt_desync_frames_bucket_total{bucket="gt_10"} 4391
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 16995
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 16251
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 738
telemt_user_connections_total{user="hello"} 2350075
telemt_user_connections_current{user="hello"} 1331
telemt_user_octets_from_client{user="hello"} 35072073340 (32.66 GB)
telemt_user_octets_to_client{user="hello"} 666636554444 (620.85 GB)
telemt_user_unique_ips_current{user="hello"} 364
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 101403.8 (28h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 961843
telemt_connections_bad_total 16375
telemt_handshake_timeouts_total 85389
telemt_upstream_connect_attempt_total 31462
telemt_upstream_connect_success_total 28495
telemt_upstream_connect_fail_total 2967
telemt_upstream_connect_attempts_per_request{bucket="1"} 31462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12817
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2046
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2967
telemt_me_keepalive_timeout_total 2825
telemt_me_reconnect_attempts_total 22560
telemt_me_reconnect_success_total 20450
telemt_me_reader_eof_total 21647
telemt_me_idle_close_by_peer_total 21644
telemt_me_route_drop_no_conn_total 363463
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 802399
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3160
telemt_desync_full_logged_total 1021
telemt_desync_suppressed_total 2139
telemt_desync_frames_bucket_total{bucket="1_2"} 990
telemt_desync_frames_bucket_total{bucket="3_10"} 1127
telemt_desync_frames_bucket_total{bucket="gt_10"} 1043
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 20735
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 20427
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 285
telemt_user_connections_total{user="hello"} 804859
telemt_user_connections_current{user="hello"} 432
telemt_user_octets_from_client{user="hello"} 9728552298 (9.06 GB)
telemt_user_octets_to_client{user="hello"} 231905985388 (215.98 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 101403.8 (28h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1654353
telemt_connections_bad_total 10438
telemt_handshake_timeouts_total 133273
telemt_upstream_connect_attempt_total 26327
telemt_upstream_connect_success_total 25999
telemt_upstream_connect_fail_total 328
telemt_upstream_connect_attempts_per_request{bucket="1"} 26327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11852
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 132
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 328
telemt_me_keepalive_timeout_total 1956
telemt_me_reconnect_attempts_total 46831
telemt_me_reconnect_success_total 19800
telemt_me_reader_eof_total 21501
telemt_me_idle_close_by_peer_total 21501
telemt_me_route_drop_no_conn_total 601403
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1447704
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3978
telemt_desync_full_logged_total 1163
telemt_desync_suppressed_total 2815
telemt_desync_frames_bucket_total{bucket="1_2"} 934
telemt_desync_frames_bucket_total{bucket="3_10"} 1510
telemt_desync_frames_bucket_total{bucket="gt_10"} 1534
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 20921
telemt_me_refill_failed_total 839
telemt_me_writer_restored_same_endpoint_total 19788
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1121
telemt_user_connections_total{user="hello"} 1447379
telemt_user_connections_current{user="hello"} 779
telemt_user_octets_from_client{user="hello"} 18004542193 (16.77 GB)
telemt_user_octets_to_client{user="hello"} 441716036877 (411.38 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 101404.3 (28h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1178491
telemt_connections_bad_total 78194
telemt_handshake_timeouts_total 109370
telemt_upstream_connect_attempt_total 27287
telemt_upstream_connect_success_total 27287
telemt_upstream_connect_attempts_per_request{bucket="1"} 27287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14879
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12402
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1415
telemt_me_reconnect_attempts_total 26827
telemt_me_reconnect_success_total 22217
telemt_me_reader_eof_total 23603
telemt_me_idle_close_by_peer_total 23602
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 393014
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 956481
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2013
telemt_desync_full_logged_total 768
telemt_desync_suppressed_total 1245
telemt_desync_frames_bucket_total{bucket="1_2"} 727
telemt_desync_frames_bucket_total{bucket="3_10"} 694
telemt_desync_frames_bucket_total{bucket="gt_10"} 592
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 22596
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 22184
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 379
telemt_user_connections_total{user="hello"} 955742
telemt_user_connections_current{user="hello"} 481
telemt_user_octets_from_client{user="hello"} 11383254844 (10.60 GB)
telemt_user_octets_to_client{user="hello"} 290790799952 (270.82 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 6080.2 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103028
telemt_connections_bad_total 315
telemt_handshake_timeouts_total 587
telemt_upstream_connect_attempt_total 1722
telemt_upstream_connect_success_total 1721
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1389
telemt_me_reconnect_success_total 1373
telemt_me_reader_eof_total 1398
telemt_me_idle_close_by_peer_total 1398
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 34995
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95094
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 202
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 136
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 85
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1385
telemt_me_writer_restored_same_endpoint_total 1350
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 95074
telemt_user_connections_current{user="hello"} 658
telemt_user_octets_from_client{user="hello"} 6275131788 (5.84 GB)
telemt_user_octets_to_client{user="hello"} 33386060944 (31.09 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 74
```