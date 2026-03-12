# Server Metrics 2026-03-12 11:26:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 19646.0 (5h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 665087
telemt_connections_bad_total 1492
telemt_handshake_timeouts_total 3814
telemt_upstream_connect_attempt_total 3712
telemt_upstream_connect_success_total 3686
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 3712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1640
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 314
telemt_me_reconnect_attempts_total 6572
telemt_me_reconnect_success_total 2681
telemt_me_reader_eof_total 2901
telemt_me_idle_close_by_peer_total 2901
telemt_me_route_drop_no_conn_total 231247
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 641007
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3179
telemt_desync_full_logged_total 802
telemt_desync_suppressed_total 2377
telemt_desync_frames_bucket_total{bucket="1_2"} 806
telemt_desync_frames_bucket_total{bucket="3_10"} 1174
telemt_desync_frames_bucket_total{bucket="gt_10"} 1199
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2830
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2668
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 640864
telemt_user_connections_current{user="hello"} 1369
telemt_user_octets_from_client{user="hello"} 11391145904 (10.61 GB)
telemt_user_octets_to_client{user="hello"} 176980124996 (164.83 GB)
telemt_user_unique_ips_current{user="hello"} 408
telemt_user_unique_ips_recent_window{user="hello"} 213
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 49266.6 (13h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 350193
telemt_connections_bad_total 4015
telemt_handshake_timeouts_total 13214
telemt_upstream_connect_attempt_total 12180
telemt_upstream_connect_success_total 12174
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 12180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6184
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 819
telemt_me_reconnect_attempts_total 9587
telemt_me_reconnect_success_total 9533
telemt_me_reader_eof_total 10133
telemt_me_idle_close_by_peer_total 10133
telemt_me_route_drop_no_conn_total 100575
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 312384
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 804
telemt_desync_full_logged_total 284
telemt_desync_suppressed_total 520
telemt_desync_frames_bucket_total{bucket="1_2"} 281
telemt_desync_frames_bucket_total{bucket="3_10"} 281
telemt_desync_frames_bucket_total{bucket="gt_10"} 242
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 9617
telemt_me_writer_restored_same_endpoint_total 9524
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 312854
telemt_user_connections_current{user="hello"} 571
telemt_user_octets_from_client{user="hello"} 4208873459 (3.92 GB)
telemt_user_octets_to_client{user="hello"} 110573618746 (102.98 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 49266.4 (13h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 827698
telemt_connections_bad_total 4180
telemt_handshake_timeouts_total 60880
telemt_upstream_connect_attempt_total 12169
telemt_upstream_connect_success_total 12164
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 12169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6699
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5411
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 700
telemt_me_reconnect_attempts_total 9438
telemt_me_reconnect_success_total 9359
telemt_me_reader_eof_total 9845
telemt_me_idle_close_by_peer_total 9845
telemt_me_route_drop_no_conn_total 194211
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 547878
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2466
telemt_desync_full_logged_total 733
telemt_desync_suppressed_total 1733
telemt_desync_frames_bucket_total{bucket="1_2"} 315
telemt_desync_frames_bucket_total{bucket="3_10"} 861
telemt_desync_frames_bucket_total{bucket="gt_10"} 1290
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 9379
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 9318
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 548125
telemt_user_connections_current{user="hello"} 852
telemt_user_octets_from_client{user="hello"} 7452363820 (6.94 GB)
telemt_user_octets_to_client{user="hello"} 174390436549 (162.41 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 267
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 49266.9 (13h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 441986
telemt_connections_bad_total 2491
telemt_handshake_timeouts_total 39092
telemt_upstream_connect_attempt_total 13140
telemt_upstream_connect_success_total 13088
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 13140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5640
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 979
telemt_me_reconnect_attempts_total 10674
telemt_me_reconnect_success_total 10631
telemt_me_reader_eof_total 11270
telemt_me_idle_close_by_peer_total 11270
telemt_me_route_drop_no_conn_total 147290
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 370905
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 759
telemt_desync_full_logged_total 267
telemt_desync_suppressed_total 492
telemt_desync_frames_bucket_total{bucket="1_2"} 231
telemt_desync_frames_bucket_total{bucket="3_10"} 318
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 10705
telemt_me_writer_restored_same_endpoint_total 10610
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 370730
telemt_user_connections_current{user="hello"} 584
telemt_user_octets_from_client{user="hello"} 4299551916 (4.00 GB)
telemt_user_octets_to_client{user="hello"} 140255232956 (130.62 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 49266.6 (13h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 503808
telemt_connections_bad_total 1665
telemt_handshake_timeouts_total 3827
telemt_upstream_connect_attempt_total 15966
telemt_upstream_connect_success_total 15776
telemt_upstream_connect_fail_total 190
telemt_upstream_connect_attempts_per_request{bucket="1"} 15966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7528
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 190
telemt_me_keepalive_timeout_total 770
telemt_me_reconnect_attempts_total 14838
telemt_me_reconnect_success_total 13313
telemt_me_reader_eof_total 13831
telemt_me_idle_close_by_peer_total 13831
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 164594
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 471920
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1956
telemt_desync_full_logged_total 652
telemt_desync_suppressed_total 1304
telemt_desync_frames_bucket_total{bucket="1_2"} 581
telemt_desync_frames_bucket_total{bucket="3_10"} 677
telemt_desync_frames_bucket_total{bucket="gt_10"} 698
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 13491
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 13287
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 471846
telemt_user_connections_current{user="hello"} 827
telemt_user_octets_from_client{user="hello"} 5363658872 (5.00 GB)
telemt_user_octets_to_client{user="hello"} 115950600000 (107.99 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 121
```