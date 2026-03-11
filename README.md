# Server Metrics 2026-03-11 02:27:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 43247.3 (12h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 846220
telemt_connections_bad_total 10043
telemt_handshake_timeouts_total 13965
telemt_upstream_connect_attempt_total 9391
telemt_upstream_connect_success_total 9382
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 9391
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4686
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4637
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 497
telemt_me_reconnect_attempts_total 18839
telemt_me_reconnect_success_total 7170
telemt_me_reader_eof_total 7833
telemt_me_idle_close_by_peer_total 7833
telemt_me_route_drop_no_conn_total 340645
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 797676
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3662
telemt_desync_full_logged_total 1033
telemt_desync_suppressed_total 2629
telemt_desync_frames_bucket_total{bucket="1_2"} 1072
telemt_desync_frames_bucket_total{bucket="3_10"} 1370
telemt_desync_frames_bucket_total{bucket="gt_10"} 1220
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 7597
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 7164
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 427
telemt_user_connections_total{user="hello"} 797412
telemt_user_connections_current{user="hello"} 470
telemt_user_octets_from_client{user="hello"} 10817739816 (10.07 GB)
telemt_user_octets_to_client{user="hello"} 238910398056 (222.50 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 43303.9 (12h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 359857
telemt_connections_bad_total 2413
telemt_handshake_timeouts_total 18134
telemt_upstream_connect_attempt_total 17018
telemt_upstream_connect_success_total 14128
telemt_upstream_connect_fail_total 2890
telemt_upstream_connect_attempts_per_request{bucket="1"} 17018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5692
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2890
telemt_me_keepalive_timeout_total 1739
telemt_me_reconnect_attempts_total 9784
telemt_me_reconnect_success_total 8967
telemt_me_reader_eof_total 9465
telemt_me_idle_close_by_peer_total 9463
telemt_me_route_drop_no_conn_total 176944
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 308376
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1788
telemt_desync_full_logged_total 514
telemt_desync_suppressed_total 1274
telemt_desync_frames_bucket_total{bucket="1_2"} 548
telemt_desync_frames_bucket_total{bucket="3_10"} 637
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 9081
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 8946
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 310646
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 2915288006 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 72868892768 (67.86 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 43303.8 (12h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 599648
telemt_connections_bad_total 4904
telemt_handshake_timeouts_total 34526
telemt_upstream_connect_attempt_total 11818
telemt_upstream_connect_success_total 11657
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 11818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5143
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 533
telemt_me_reconnect_attempts_total 19439
telemt_me_reconnect_success_total 8373
telemt_me_reader_eof_total 9096
telemt_me_idle_close_by_peer_total 9096
telemt_me_route_drop_no_conn_total 203620
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 531448
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1545
telemt_desync_full_logged_total 450
telemt_desync_suppressed_total 1095
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 538
telemt_desync_frames_bucket_total{bucket="gt_10"} 663
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 8833
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 8362
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 460
telemt_user_connections_total{user="hello"} 532349
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 6995251053 (6.51 GB)
telemt_user_octets_to_client{user="hello"} 163298733129 (152.08 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 43304.2 (12h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 448986
telemt_connections_bad_total 40994
telemt_handshake_timeouts_total 43412
telemt_upstream_connect_attempt_total 12634
telemt_upstream_connect_success_total 12634
telemt_upstream_connect_attempts_per_request{bucket="1"} 12634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7113
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 436
telemt_me_reconnect_attempts_total 11459
telemt_me_reconnect_success_total 10422
telemt_me_reader_eof_total 11038
telemt_me_idle_close_by_peer_total 11038
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 134737
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 350990
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 765
telemt_desync_full_logged_total 303
telemt_desync_suppressed_total 462
telemt_desync_frames_bucket_total{bucket="1_2"} 288
telemt_desync_frames_bucket_total{bucket="3_10"} 268
telemt_desync_frames_bucket_total{bucket="gt_10"} 209
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 10548
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 10403
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 350659
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 4323744084 (4.03 GB)
telemt_user_octets_to_client{user="hello"} 94056384548 (87.60 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 43303.7 (12h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 473546
telemt_connections_bad_total 5790
telemt_handshake_timeouts_total 3007
telemt_upstream_connect_attempt_total 12784
telemt_upstream_connect_success_total 12730
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 12784
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6034
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 527
telemt_me_reconnect_attempts_total 14254
telemt_me_reconnect_success_total 10480
telemt_me_reader_eof_total 11041
telemt_me_idle_close_by_peer_total 11041
telemt_me_route_drop_no_conn_total 153648
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 432163
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2308
telemt_desync_full_logged_total 898
telemt_desync_suppressed_total 1410
telemt_desync_frames_bucket_total{bucket="1_2"} 857
telemt_desync_frames_bucket_total{bucket="3_10"} 979
telemt_desync_frames_bucket_total{bucket="gt_10"} 472
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 10733
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 10480
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 431835
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 8474551060 (7.89 GB)
telemt_user_octets_to_client{user="hello"} 152781191832 (142.29 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 39
```