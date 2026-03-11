# Server Metrics 2026-03-11 08:44:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 65816.2 (18h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1368046
telemt_connections_bad_total 15746
telemt_handshake_timeouts_total 40103
telemt_upstream_connect_attempt_total 13633
telemt_upstream_connect_success_total 13624
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 13633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6670
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 753
telemt_me_reconnect_attempts_total 21974
telemt_me_reconnect_success_total 10288
telemt_me_reader_eof_total 11154
telemt_me_idle_close_by_peer_total 11154
telemt_me_route_drop_no_conn_total 503816
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1241062
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6087
telemt_desync_full_logged_total 1689
telemt_desync_suppressed_total 4398
telemt_desync_frames_bucket_total{bucket="1_2"} 1600
telemt_desync_frames_bucket_total{bucket="3_10"} 2315
telemt_desync_frames_bucket_total{bucket="gt_10"} 2172
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10753
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 10282
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 465
telemt_user_connections_total{user="hello"} 1240737
telemt_user_connections_current{user="hello"} 1284
telemt_user_octets_from_client{user="hello"} 16516600752 (15.38 GB)
telemt_user_octets_to_client{user="hello"} 359576884260 (334.88 GB)
telemt_user_unique_ips_current{user="hello"} 342
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 65872.9 (18h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 529742
telemt_connections_bad_total 8848
telemt_handshake_timeouts_total 29306
telemt_upstream_connect_attempt_total 22661
telemt_upstream_connect_success_total 19735
telemt_upstream_connect_fail_total 2926
telemt_upstream_connect_attempts_per_request{bucket="1"} 22661
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8532
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2926
telemt_me_keepalive_timeout_total 2061
telemt_me_reconnect_attempts_total 14305
telemt_me_reconnect_success_total 13474
telemt_me_reader_eof_total 14262
telemt_me_idle_close_by_peer_total 14260
telemt_me_route_drop_no_conn_total 223759
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 448463
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2137
telemt_desync_full_logged_total 655
telemt_desync_suppressed_total 1482
telemt_desync_frames_bucket_total{bucket="1_2"} 709
telemt_desync_frames_bucket_total{bucket="3_10"} 770
telemt_desync_frames_bucket_total{bucket="gt_10"} 658
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 13632
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 13452
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 450703
telemt_user_connections_current{user="hello"} 412
telemt_user_octets_from_client{user="hello"} 4376783886 (4.08 GB)
telemt_user_octets_to_client{user="hello"} 120424034056 (112.15 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 65872.8 (18h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 906563
telemt_connections_bad_total 7239
telemt_handshake_timeouts_total 70726
telemt_upstream_connect_attempt_total 17821
telemt_upstream_connect_success_total 17602
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 17821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7923
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_keepalive_timeout_total 756
telemt_me_reconnect_attempts_total 25572
telemt_me_reconnect_success_total 13211
telemt_me_reader_eof_total 14214
telemt_me_idle_close_by_peer_total 14214
telemt_me_route_drop_no_conn_total 301028
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 790534
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2254
telemt_desync_full_logged_total 670
telemt_desync_suppressed_total 1584
telemt_desync_frames_bucket_total{bucket="1_2"} 538
telemt_desync_frames_bucket_total{bucket="3_10"} 818
telemt_desync_frames_bucket_total{bucket="gt_10"} 898
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 13764
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 13200
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 553
telemt_user_connections_total{user="hello"} 791344
telemt_user_connections_current{user="hello"} 704
telemt_user_octets_from_client{user="hello"} 9326628677 (8.69 GB)
telemt_user_octets_to_client{user="hello"} 239179346957 (222.75 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 65873.4 (18h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 676365
telemt_connections_bad_total 61605
telemt_handshake_timeouts_total 66013
telemt_upstream_connect_attempt_total 18242
telemt_upstream_connect_success_total 18242
telemt_upstream_connect_attempts_per_request{bucket="1"} 18242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8083
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 688
telemt_me_reconnect_attempts_total 15985
telemt_me_reconnect_success_total 14933
telemt_me_reader_eof_total 15868
telemt_me_idle_close_by_peer_total 15867
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 210118
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 527388
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1236
telemt_desync_full_logged_total 465
telemt_desync_suppressed_total 771
telemt_desync_frames_bucket_total{bucket="1_2"} 410
telemt_desync_frames_bucket_total{bucket="3_10"} 469
telemt_desync_frames_bucket_total{bucket="gt_10"} 357
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 15110
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 14911
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 526763
telemt_user_connections_current{user="hello"} 511
telemt_user_octets_from_client{user="hello"} 6209606204 (5.78 GB)
telemt_user_octets_to_client{user="hello"} 147252534024 (137.14 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 65873.1 (18h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 713095
telemt_connections_bad_total 5982
telemt_handshake_timeouts_total 6733
telemt_upstream_connect_attempt_total 18091
telemt_upstream_connect_success_total 18018
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 18091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9285
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8585
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 725
telemt_me_reconnect_attempts_total 18383
telemt_me_reconnect_success_total 14591
telemt_me_reader_eof_total 15426
telemt_me_idle_close_by_peer_total 15426
telemt_me_route_drop_no_conn_total 240299
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 647181
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2843
telemt_desync_full_logged_total 1073
telemt_desync_suppressed_total 1770
telemt_desync_frames_bucket_total{bucket="1_2"} 996
telemt_desync_frames_bucket_total{bucket="3_10"} 1184
telemt_desync_frames_bucket_total{bucket="gt_10"} 663
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 14896
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 14591
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 305
telemt_user_connections_total{user="hello"} 646875
telemt_user_connections_current{user="hello"} 686
telemt_user_octets_from_client{user="hello"} 10505998099 (9.78 GB)
telemt_user_octets_to_client{user="hello"} 234278296546 (218.19 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 112
```