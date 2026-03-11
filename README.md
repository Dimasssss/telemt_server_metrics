# Server Metrics 2026-03-11 11:06:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 74385.0 (20h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1656959
telemt_connections_bad_total 25366
telemt_handshake_timeouts_total 43296
telemt_upstream_connect_attempt_total 15514
telemt_upstream_connect_success_total 15505
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 15514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7616
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 806
telemt_me_reconnect_attempts_total 23446
telemt_me_reconnect_success_total 11748
telemt_me_reader_eof_total 12684
telemt_me_idle_close_by_peer_total 12684
telemt_me_route_drop_no_conn_total 611111
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1506509
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7793
telemt_desync_full_logged_total 2119
telemt_desync_suppressed_total 5674
telemt_desync_frames_bucket_total{bucket="1_2"} 2010
telemt_desync_frames_bucket_total{bucket="3_10"} 2955
telemt_desync_frames_bucket_total{bucket="gt_10"} 2828
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 12230
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 11742
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 482
telemt_user_connections_total{user="hello"} 1505088
telemt_user_connections_current{user="hello"} 1287
telemt_user_octets_from_client{user="hello"} 19606496796 (18.26 GB)
telemt_user_octets_to_client{user="hello"} 429535473040 (400.04 GB)
telemt_user_unique_ips_current{user="hello"} 348
telemt_user_unique_ips_recent_window{user="hello"} 196
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 74441.8 (20h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 632162
telemt_connections_bad_total 10715
telemt_handshake_timeouts_total 39383
telemt_upstream_connect_attempt_total 24520
telemt_upstream_connect_success_total 21587
telemt_upstream_connect_fail_total 2933
telemt_upstream_connect_attempts_per_request{bucket="1"} 24520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9470
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2933
telemt_me_keepalive_timeout_total 2183
telemt_me_reconnect_attempts_total 15766
telemt_me_reconnect_success_total 14919
telemt_me_reader_eof_total 15802
telemt_me_idle_close_by_peer_total 15800
telemt_me_route_drop_no_conn_total 257643
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 535707
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2448
telemt_desync_full_logged_total 767
telemt_desync_suppressed_total 1681
telemt_desync_frames_bucket_total{bucket="1_2"} 799
telemt_desync_frames_bucket_total{bucket="3_10"} 881
telemt_desync_frames_bucket_total{bucket="gt_10"} 768
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 15105
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 14897
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 537931
telemt_user_connections_current{user="hello"} 497
telemt_user_octets_from_client{user="hello"} 5535982798 (5.16 GB)
telemt_user_octets_to_client{user="hello"} 150311393912 (139.99 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 74441.6 (20h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1097628
telemt_connections_bad_total 7737
telemt_handshake_timeouts_total 105118
telemt_upstream_connect_attempt_total 20061
telemt_upstream_connect_success_total 19814
telemt_upstream_connect_fail_total 247
telemt_upstream_connect_attempts_per_request{bucket="1"} 20061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8921
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 247
telemt_me_keepalive_timeout_total 821
telemt_me_reconnect_attempts_total 28632
telemt_me_reconnect_success_total 15008
telemt_me_reader_eof_total 16115
telemt_me_idle_close_by_peer_total 16115
telemt_me_route_drop_no_conn_total 366540
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 943951
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2627
telemt_desync_full_logged_total 779
telemt_desync_suppressed_total 1848
telemt_desync_frames_bucket_total{bucket="1_2"} 619
telemt_desync_frames_bucket_total{bucket="3_10"} 985
telemt_desync_frames_bucket_total{bucket="gt_10"} 1023
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 15623
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 14997
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 615
telemt_user_connections_total{user="hello"} 944698
telemt_user_connections_current{user="hello"} 791
telemt_user_octets_from_client{user="hello"} 11030264445 (10.27 GB)
telemt_user_octets_to_client{user="hello"} 286832485149 (267.13 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 74442.1 (20h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 796448
telemt_connections_bad_total 69975
telemt_handshake_timeouts_total 74684
telemt_upstream_connect_attempt_total 20271
telemt_upstream_connect_success_total 20271
telemt_upstream_connect_attempts_per_request{bucket="1"} 20271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9105
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 781
telemt_me_reconnect_attempts_total 17621
telemt_me_reconnect_success_total 16561
telemt_me_reader_eof_total 17585
telemt_me_idle_close_by_peer_total 17584
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 252125
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 628794
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1387
telemt_desync_full_logged_total 533
telemt_desync_suppressed_total 854
telemt_desync_frames_bucket_total{bucket="1_2"} 490
telemt_desync_frames_bucket_total{bucket="3_10"} 508
telemt_desync_frames_bucket_total{bucket="gt_10"} 389
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 16760
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 16536
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 628162
telemt_user_connections_current{user="hello"} 460
telemt_user_octets_from_client{user="hello"} 7204606480 (6.71 GB)
telemt_user_octets_to_client{user="hello"} 179131847636 (166.83 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 74441.9 (20h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 853748
telemt_connections_bad_total 6094
telemt_handshake_timeouts_total 8197
telemt_upstream_connect_attempt_total 20145
telemt_upstream_connect_success_total 20061
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 20145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9622
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 162
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 855
telemt_me_reconnect_attempts_total 20030
telemt_me_reconnect_success_total 16231
telemt_me_reader_eof_total 17131
telemt_me_idle_close_by_peer_total 17131
telemt_me_route_drop_no_conn_total 297846
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 774470
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3202
telemt_desync_full_logged_total 1186
telemt_desync_suppressed_total 2016
telemt_desync_frames_bucket_total{bucket="1_2"} 1096
telemt_desync_frames_bucket_total{bucket="3_10"} 1278
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 16554
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 16231
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 323
telemt_user_connections_total{user="hello"} 774238
telemt_user_connections_current{user="hello"} 732
telemt_user_octets_from_client{user="hello"} 11664610435 (10.86 GB)
telemt_user_octets_to_client{user="hello"} 282092904622 (262.72 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 99
```