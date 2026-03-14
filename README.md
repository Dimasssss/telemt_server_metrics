# Server Metrics 2026-03-14 14:56:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 5916.2 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236899
telemt_connections_bad_total 6731
telemt_handshake_timeouts_total 3229
telemt_upstream_connect_attempt_total 1190
telemt_upstream_connect_success_total 1183
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 570
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 1617
telemt_me_reconnect_success_total 834
telemt_me_reader_eof_total 864
telemt_me_idle_close_by_peer_total 864
telemt_me_route_drop_no_conn_total 91895
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 217010
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 447
telemt_desync_full_logged_total 162
telemt_desync_suppressed_total 285
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 170
telemt_desync_frames_bucket_total{bucket="gt_10"} 172
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 868
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 825
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 217002
telemt_user_connections_current{user="hello"} 1617
telemt_user_octets_from_client{user="hello"} 3722577296 (3.47 GB)
telemt_user_octets_to_client{user="hello"} 62100523364 (57.84 GB)
telemt_user_unique_ips_current{user="hello"} 471
telemt_user_unique_ips_recent_window{user="hello"} 213
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 5921.6 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94525
telemt_connections_bad_total 8258
telemt_handshake_timeouts_total 3540
telemt_upstream_connect_attempt_total 1264
telemt_upstream_connect_success_total 1254
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 486
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 927
telemt_me_reconnect_success_total 905
telemt_me_reader_eof_total 913
telemt_me_idle_close_by_peer_total 913
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 29489
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75679
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 445
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 344
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 148
telemt_desync_frames_bucket_total{bucket="gt_10"} 121
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 924
telemt_me_writer_restored_same_endpoint_total 894
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 75638
telemt_user_connections_current{user="hello"} 675
telemt_user_octets_from_client{user="hello"} 1025480392 (977.97 MB)
telemt_user_octets_to_client{user="hello"} 33591357000 (31.28 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 5784.3 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177286
telemt_connections_bad_total 660
telemt_handshake_timeouts_total 34705
telemt_upstream_connect_attempt_total 1350
telemt_upstream_connect_success_total 1345
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 715
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 627
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 2141
telemt_me_reconnect_success_total 1001
telemt_me_reader_eof_total 1022
telemt_me_idle_close_by_peer_total 1022
telemt_me_route_drop_no_conn_total 48789
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 133043
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 221
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 163
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1032
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 968
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 132970
telemt_user_connections_current{user="hello"} 949
telemt_user_octets_from_client{user="hello"} 1984624280 (1.85 GB)
telemt_user_octets_to_client{user="hello"} 40624966668 (37.83 GB)
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 5638.8 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91660
telemt_connections_bad_total 23003
telemt_handshake_timeouts_total 12818
telemt_upstream_connect_attempt_total 1504
telemt_upstream_connect_success_total 1504
telemt_upstream_connect_attempts_per_request{bucket="1"} 1504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 794
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 687
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 1172
telemt_me_reconnect_success_total 1164
telemt_me_reader_eof_total 1173
telemt_me_idle_close_by_peer_total 1173
telemt_me_route_drop_no_conn_total 20904
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54788
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 94
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 59
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1164
telemt_me_writer_restored_same_endpoint_total 1163
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 20
telemt_user_connections_total{user="hello"} 54754
telemt_user_connections_current{user="hello"} 482
telemt_user_octets_from_client{user="hello"} 1154355828 (1.08 GB)
telemt_user_octets_to_client{user="hello"} 15270439968 (14.22 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 5934.2 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94689
telemt_connections_bad_total 186
telemt_handshake_timeouts_total 1599
telemt_upstream_connect_attempt_total 1372
telemt_upstream_connect_success_total 1344
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 1372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 627
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 1657
telemt_me_reconnect_success_total 1005
telemt_me_reader_eof_total 1048
telemt_me_idle_close_by_peer_total 1048
telemt_me_route_drop_no_conn_total 32012
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86876
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 302
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 101
telemt_desync_frames_bucket_total{bucket="gt_10"} 97
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1049
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 987
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 86879
telemt_user_connections_current{user="hello"} 773
telemt_user_octets_from_client{user="hello"} 1316047880 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 29654828648 (27.62 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 126
```