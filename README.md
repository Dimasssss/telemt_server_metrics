# Server Metrics 2026-03-13 12:22:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 109412.5 (30h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3252747
telemt_connections_bad_total 36553
telemt_handshake_timeouts_total 56503
telemt_upstream_connect_attempt_total 21651
telemt_upstream_connect_success_total 21533
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 21651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10383
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 2082
telemt_me_reconnect_attempts_total 26163
telemt_me_reconnect_success_total 16082
telemt_me_reader_eof_total 17288
telemt_me_idle_close_by_peer_total 17287
telemt_me_route_drop_no_conn_total 1205972
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2980117
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12651
telemt_desync_full_logged_total 3276
telemt_desync_suppressed_total 9375
telemt_desync_frames_bucket_total{bucket="1_2"} 3228
telemt_desync_frames_bucket_total{bucket="3_10"} 4764
telemt_desync_frames_bucket_total{bucket="gt_10"} 4659
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 16617
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16069
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 535
telemt_user_connections_total{user="hello"} 2980048
telemt_user_connections_current{user="hello"} 1788
telemt_user_octets_from_client{user="hello"} 41191249636 (38.36 GB)
telemt_user_octets_to_client{user="hello"} 961768903628 (895.72 GB)
telemt_user_unique_ips_current{user="hello"} 451
telemt_user_unique_ips_recent_window{user="hello"} 223
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 9076.1 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122534
telemt_connections_bad_total 6867
telemt_handshake_timeouts_total 2838
telemt_upstream_connect_attempt_total 2279
telemt_upstream_connect_success_total 2207
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 2279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1057
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 49
telemt_me_reconnect_attempts_total 2916
telemt_me_reconnect_success_total 1690
telemt_me_reader_eof_total 1766
telemt_me_idle_close_by_peer_total 1766
telemt_me_route_drop_no_conn_total 43281
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109751
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 248
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 182
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 103
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1739
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 1683
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 109776
telemt_user_connections_current{user="hello"} 596
telemt_user_octets_from_client{user="hello"} 1083936976 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 28883980976 (26.90 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 139032.9 (38h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2472593
telemt_connections_bad_total 25790
telemt_handshake_timeouts_total 163654
telemt_upstream_connect_attempt_total 31704
telemt_upstream_connect_success_total 31694
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 31704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15023
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3160
telemt_me_reconnect_attempts_total 26965
telemt_me_reconnect_success_total 24420
telemt_me_reader_eof_total 25887
telemt_me_idle_close_by_peer_total 25886
telemt_me_route_drop_no_conn_total 824400
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2005555
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6705
telemt_desync_full_logged_total 2162
telemt_desync_suppressed_total 4543
telemt_desync_frames_bucket_total{bucket="1_2"} 1059
telemt_desync_frames_bucket_total{bucket="3_10"} 2452
telemt_desync_frames_bucket_total{bucket="gt_10"} 3194
telemt_pool_swap_total 129
telemt_me_writer_removed_unexpected_total 24702
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 24379
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 282
telemt_user_connections_total{user="hello"} 2004972
telemt_user_connections_current{user="hello"} 918
telemt_user_octets_from_client{user="hello"} 34042955432 (31.70 GB)
telemt_user_octets_to_client{user="hello"} 718827640157 (669.46 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 139033.3 (38h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1577410
telemt_connections_bad_total 17865
telemt_handshake_timeouts_total 110429
telemt_upstream_connect_attempt_total 45013
telemt_upstream_connect_success_total 42694
telemt_upstream_connect_fail_total 2182
telemt_upstream_connect_attempts_per_request{bucket="1"} 44739
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16821
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2181
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11824
telemt_me_reconnect_attempts_total 38872
telemt_me_reconnect_success_total 29908
telemt_me_reader_eof_total 32165
telemt_me_idle_close_by_peer_total 32158
telemt_me_route_drop_no_conn_total 559080
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1314164
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2506
telemt_desync_full_logged_total 832
telemt_desync_suppressed_total 1674
telemt_desync_frames_bucket_total{bucket="1_2"} 677
telemt_desync_frames_bucket_total{bucket="3_10"} 976
telemt_desync_frames_bucket_total{bucket="gt_10"} 853
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 30407
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 29884
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 499
telemt_user_connections_total{user="hello"} 1318888
telemt_user_connections_current{user="hello"} 626
telemt_user_octets_from_client{user="hello"} 19631496253 (18.28 GB)
telemt_user_octets_to_client{user="hello"} 514748993382 (479.40 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 8468.9 (2h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122787
telemt_connections_bad_total 702
telemt_handshake_timeouts_total 937
telemt_upstream_connect_attempt_total 1702
telemt_upstream_connect_success_total 1636
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 1702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 932
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 9230
telemt_me_reconnect_success_total 1160
telemt_me_reader_eof_total 1388
telemt_me_idle_close_by_peer_total 1388
telemt_me_route_drop_no_conn_total 47953
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117107
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 445
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 294
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 139
telemt_desync_frames_bucket_total{bucket="gt_10"} 84
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1404
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 1156
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 244
telemt_user_connections_total{user="hello"} 117103
telemt_user_connections_current{user="hello"} 798
telemt_user_octets_from_client{user="hello"} 1331224364 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 38415699036 (35.78 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 107
```