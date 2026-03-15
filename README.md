# Server Metrics 2026-03-15 11:31:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 47828.1 (13h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1263016
telemt_connections_bad_total 78162
telemt_handshake_timeouts_total 10534
telemt_upstream_connect_attempt_total 9593
telemt_upstream_connect_success_total 9551
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 9593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4449
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 9645
telemt_me_reconnect_success_total 7139
telemt_me_reader_eof_total 7607
telemt_me_idle_close_by_peer_total 7607
telemt_me_route_drop_no_conn_total 420387
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1062338
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4080
telemt_desync_full_logged_total 1148
telemt_desync_suppressed_total 2932
telemt_desync_frames_bucket_total{bucket="1_2"} 986
telemt_desync_frames_bucket_total{bucket="3_10"} 1609
telemt_desync_frames_bucket_total{bucket="gt_10"} 1485
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7321
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 7128
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 1062130
telemt_user_connections_current{user="hello"} 2169
telemt_user_octets_from_client{user="hello"} 14893885020 (13.87 GB)
telemt_user_octets_to_client{user="hello"} 429337657688 (399.85 GB)
telemt_user_unique_ips_current{user="hello"} 614
telemt_user_unique_ips_recent_window{user="hello"} 322
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 47828.8 (13h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 493707
telemt_connections_bad_total 26457
telemt_handshake_timeouts_total 21937
telemt_upstream_connect_attempt_total 12495
telemt_upstream_connect_success_total 12430
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 12495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5593
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 9761
telemt_me_reconnect_success_total 9698
telemt_me_reader_eof_total 10261
telemt_me_idle_close_by_peer_total 10261
telemt_me_route_drop_no_conn_total 126764
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 389864
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1413
telemt_desync_full_logged_total 492
telemt_desync_suppressed_total 921
telemt_desync_frames_bucket_total{bucket="1_2"} 523
telemt_desync_frames_bucket_total{bucket="3_10"} 509
telemt_desync_frames_bucket_total{bucket="gt_10"} 381
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 9802
telemt_me_writer_restored_same_endpoint_total 9686
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 390134
telemt_user_connections_current{user="hello"} 786
telemt_user_octets_from_client{user="hello"} 5603084727 (5.22 GB)
telemt_user_octets_to_client{user="hello"} 146788706160 (136.71 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 47828.8 (13h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 964551
telemt_connections_bad_total 31236
telemt_handshake_timeouts_total 95222
telemt_upstream_connect_attempt_total 10539
telemt_upstream_connect_success_total 10490
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 10539
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5014
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 8120
telemt_me_reconnect_success_total 8066
telemt_me_reader_eof_total 8535
telemt_me_idle_close_by_peer_total 8535
telemt_me_route_drop_no_conn_total 274754
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 680167
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1674
telemt_desync_full_logged_total 595
telemt_desync_suppressed_total 1079
telemt_desync_frames_bucket_total{bucket="1_2"} 371
telemt_desync_frames_bucket_total{bucket="3_10"} 618
telemt_desync_frames_bucket_total{bucket="gt_10"} 685
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 8174
telemt_me_writer_restored_same_endpoint_total 8047
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 678783
telemt_user_connections_current{user="hello"} 1230
telemt_user_octets_from_client{user="hello"} 10118744308 (9.42 GB)
telemt_user_octets_to_client{user="hello"} 263684782280 (245.58 GB)
telemt_user_unique_ips_current{user="hello"} 377
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 47828.7 (13h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 504746
telemt_connections_bad_total 62387
telemt_handshake_timeouts_total 27025
telemt_upstream_connect_attempt_total 14193
telemt_upstream_connect_success_total 13828
telemt_upstream_connect_fail_total 365
telemt_upstream_connect_attempts_per_request{bucket="1"} 14193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7216
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 365
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 34171
telemt_me_reconnect_success_total 11405
telemt_me_reader_eof_total 12451
telemt_me_idle_close_by_peer_total 12451
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 141969
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 377951
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 945
telemt_desync_full_logged_total 240
telemt_desync_suppressed_total 705
telemt_desync_frames_bucket_total{bucket="1_2"} 245
telemt_desync_frames_bucket_total{bucket="3_10"} 383
telemt_desync_frames_bucket_total{bucket="gt_10"} 317
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12224
telemt_me_refill_failed_total 711
telemt_me_writer_restored_same_endpoint_total 11373
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 819
telemt_user_connections_total{user="hello"} 377851
telemt_user_connections_current{user="hello"} 705
telemt_user_octets_from_client{user="hello"} 4631887724 (4.31 GB)
telemt_user_octets_to_client{user="hello"} 118173102064 (110.06 GB)
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 47829.4 (13h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 527671
telemt_connections_bad_total 6570
telemt_handshake_timeouts_total 11513
telemt_upstream_connect_attempt_total 10686
telemt_upstream_connect_success_total 10633
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 10686
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5773
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_reconnect_attempts_total 8265
telemt_me_reconnect_success_total 8220
telemt_me_reader_eof_total 8732
telemt_me_idle_close_by_peer_total 8732
telemt_me_route_drop_no_conn_total 136185
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 435394
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1710
telemt_desync_full_logged_total 555
telemt_desync_suppressed_total 1155
telemt_desync_frames_bucket_total{bucket="1_2"} 484
telemt_desync_frames_bucket_total{bucket="3_10"} 692
telemt_desync_frames_bucket_total{bucket="gt_10"} 534
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 8313
telemt_me_writer_restored_same_endpoint_total 8212
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 435416
telemt_user_connections_current{user="hello"} 790
telemt_user_octets_from_client{user="hello"} 5578000484 (5.19 GB)
telemt_user_octets_to_client{user="hello"} 160074674108 (149.08 GB)
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 138
```