# Server Metrics 2026-03-11 02:22:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 42942.2 (11h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 843186
telemt_connections_bad_total 10043
telemt_handshake_timeouts_total 13563
telemt_upstream_connect_attempt_total 9348
telemt_upstream_connect_success_total 9339
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 9348
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4613
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 495
telemt_me_reconnect_attempts_total 18805
telemt_me_reconnect_success_total 7136
telemt_me_reader_eof_total 7798
telemt_me_idle_close_by_peer_total 7798
telemt_me_route_drop_no_conn_total 339829
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 795200
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3657
telemt_desync_full_logged_total 1030
telemt_desync_suppressed_total 2627
telemt_desync_frames_bucket_total{bucket="1_2"} 1069
telemt_desync_frames_bucket_total{bucket="3_10"} 1368
telemt_desync_frames_bucket_total{bucket="gt_10"} 1220
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 7561
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 7130
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 425
telemt_user_connections_total{user="hello"} 794936
telemt_user_connections_current{user="hello"} 477
telemt_user_octets_from_client{user="hello"} 10791605192 (10.05 GB)
telemt_user_octets_to_client{user="hello"} 238616247076 (222.23 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 42998.9 (11h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 359195
telemt_connections_bad_total 2413
telemt_handshake_timeouts_total 18118
telemt_upstream_connect_attempt_total 16928
telemt_upstream_connect_success_total 14038
telemt_upstream_connect_fail_total 2890
telemt_upstream_connect_attempts_per_request{bucket="1"} 16928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5648
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2890
telemt_me_keepalive_timeout_total 1738
telemt_me_reconnect_attempts_total 9737
telemt_me_reconnect_success_total 8920
telemt_me_reader_eof_total 9417
telemt_me_idle_close_by_peer_total 9415
telemt_me_route_drop_no_conn_total 176759
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 307742
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1787
telemt_desync_full_logged_total 513
telemt_desync_suppressed_total 1274
telemt_desync_frames_bucket_total{bucket="1_2"} 547
telemt_desync_frames_bucket_total{bucket="3_10"} 637
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 9034
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 8899
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 310012
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 2911584566 (2.71 GB)
telemt_user_octets_to_client{user="hello"} 72803555136 (67.80 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 42998.7 (11h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 598288
telemt_connections_bad_total 4904
telemt_handshake_timeouts_total 34502
telemt_upstream_connect_attempt_total 11735
telemt_upstream_connect_success_total 11579
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 11735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 533
telemt_me_reconnect_attempts_total 19400
telemt_me_reconnect_success_total 8334
telemt_me_reader_eof_total 9055
telemt_me_idle_close_by_peer_total 9055
telemt_me_route_drop_no_conn_total 203200
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 530127
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1544
telemt_desync_full_logged_total 449
telemt_desync_suppressed_total 1095
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 537
telemt_desync_frames_bucket_total{bucket="gt_10"} 663
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 8792
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 8323
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 458
telemt_user_connections_total{user="hello"} 531034
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 6987983197 (6.51 GB)
telemt_user_octets_to_client{user="hello"} 162651925913 (151.48 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 42999.0 (11h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 447361
telemt_connections_bad_total 40712
telemt_handshake_timeouts_total 43198
telemt_upstream_connect_attempt_total 12519
telemt_upstream_connect_success_total 12519
telemt_upstream_connect_attempts_per_request{bucket="1"} 12519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5466
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 11387
telemt_me_reconnect_success_total 10350
telemt_me_reader_eof_total 10963
telemt_me_idle_close_by_peer_total 10963
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 134360
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 349866
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
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 10474
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 10331
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 349535
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 4319438928 (4.02 GB)
telemt_user_octets_to_client{user="hello"} 93845761076 (87.40 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 42998.9 (11h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 471958
telemt_connections_bad_total 5790
telemt_handshake_timeouts_total 3003
telemt_upstream_connect_attempt_total 12689
telemt_upstream_connect_success_total 12636
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 12689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5992
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 527
telemt_me_reconnect_attempts_total 14203
telemt_me_reconnect_success_total 10429
telemt_me_reader_eof_total 10990
telemt_me_idle_close_by_peer_total 10990
telemt_me_route_drop_no_conn_total 153314
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 430817
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2307
telemt_desync_full_logged_total 897
telemt_desync_suppressed_total 1410
telemt_desync_frames_bucket_total{bucket="1_2"} 856
telemt_desync_frames_bucket_total{bucket="3_10"} 979
telemt_desync_frames_bucket_total{bucket="gt_10"} 472
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 10682
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 10429
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 430491
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 8469783256 (7.89 GB)
telemt_user_octets_to_client{user="hello"} 152522625044 (142.05 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 32
```