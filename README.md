# Server Metrics 2026-03-13 13:18:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 112775.3 (31h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3398588
telemt_connections_bad_total 37371
telemt_handshake_timeouts_total 58607
telemt_upstream_connect_attempt_total 22180
telemt_upstream_connect_success_total 22057
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 22180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10616
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 2109
telemt_me_reconnect_attempts_total 26515
telemt_me_reconnect_success_total 16431
telemt_me_reader_eof_total 17665
telemt_me_idle_close_by_peer_total 17664
telemt_me_route_drop_no_conn_total 1259863
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3116321
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12993
telemt_desync_full_logged_total 3394
telemt_desync_suppressed_total 9599
telemt_desync_frames_bucket_total{bucket="1_2"} 3298
telemt_desync_frames_bucket_total{bucket="3_10"} 4920
telemt_desync_frames_bucket_total{bucket="gt_10"} 4775
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 16976
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16418
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 545
telemt_user_connections_total{user="hello"} 3116213
telemt_user_connections_current{user="hello"} 1746
telemt_user_octets_from_client{user="hello"} 42948761152 (40.00 GB)
telemt_user_octets_to_client{user="hello"} 999936806544 (931.26 GB)
telemt_user_unique_ips_current{user="hello"} 466
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 12439.2 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170692
telemt_connections_bad_total 9732
telemt_handshake_timeouts_total 4215
telemt_upstream_connect_attempt_total 2988
telemt_upstream_connect_success_total 2913
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 2988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1405
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 67
telemt_me_reconnect_attempts_total 3482
telemt_me_reconnect_success_total 2253
telemt_me_reader_eof_total 2370
telemt_me_idle_close_by_peer_total 2370
telemt_me_route_drop_no_conn_total 61857
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 152547
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 610
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 475
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 327
telemt_desync_frames_bucket_total{bucket="gt_10"} 173
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2309
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2246
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 152572
telemt_user_connections_current{user="hello"} 485
telemt_user_octets_from_client{user="hello"} 1552380976 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 42140772800 (39.25 GB)
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 142395.7 (39h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2559096
telemt_connections_bad_total 26715
telemt_handshake_timeouts_total 168932
telemt_upstream_connect_attempt_total 32326
telemt_upstream_connect_success_total 32316
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 32326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15356
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3196
telemt_me_reconnect_attempts_total 27415
telemt_me_reconnect_success_total 24869
telemt_me_reader_eof_total 26368
telemt_me_idle_close_by_peer_total 26367
telemt_me_route_drop_no_conn_total 858087
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2084045
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7164
telemt_desync_full_logged_total 2335
telemt_desync_suppressed_total 4829
telemt_desync_frames_bucket_total{bucket="1_2"} 1135
telemt_desync_frames_bucket_total{bucket="3_10"} 2612
telemt_desync_frames_bucket_total{bucket="gt_10"} 3417
telemt_pool_swap_total 133
telemt_me_writer_removed_unexpected_total 25157
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 24828
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 288
telemt_user_connections_total{user="hello"} 2083467
telemt_user_connections_current{user="hello"} 1056
telemt_user_octets_from_client{user="hello"} 34892238740 (32.50 GB)
telemt_user_octets_to_client{user="hello"} 748698629913 (697.28 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 142396.2 (39h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1631631
telemt_connections_bad_total 17886
telemt_handshake_timeouts_total 114728
telemt_upstream_connect_attempt_total 45688
telemt_upstream_connect_success_total 43368
telemt_upstream_connect_fail_total 2183
telemt_upstream_connect_attempts_per_request{bucket="1"} 45414
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17123
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2182
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11830
telemt_me_reconnect_attempts_total 39374
telemt_me_reconnect_success_total 30408
telemt_me_reader_eof_total 32700
telemt_me_idle_close_by_peer_total 32693
telemt_me_route_drop_no_conn_total 580882
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1363425
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2743
telemt_desync_full_logged_total 892
telemt_desync_suppressed_total 1851
telemt_desync_frames_bucket_total{bucket="1_2"} 732
telemt_desync_frames_bucket_total{bucket="3_10"} 1138
telemt_desync_frames_bucket_total{bucket="gt_10"} 873
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 30912
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 30384
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 504
telemt_user_connections_total{user="hello"} 1368145
telemt_user_connections_current{user="hello"} 669
telemt_user_octets_from_client{user="hello"} 20693104225 (19.27 GB)
telemt_user_octets_to_client{user="hello"} 533374609042 (496.74 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 11832.3 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183618
telemt_connections_bad_total 3841
telemt_handshake_timeouts_total 1606
telemt_upstream_connect_attempt_total 2382
telemt_upstream_connect_success_total 2298
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 2382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1052
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1244
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 9720
telemt_me_reconnect_success_total 1646
telemt_me_reader_eof_total 1901
telemt_me_idle_close_by_peer_total 1901
telemt_me_route_drop_no_conn_total 70617
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171779
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 600
telemt_desync_full_logged_total 195
telemt_desync_suppressed_total 405
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 220
telemt_desync_frames_bucket_total{bucket="gt_10"} 120
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1896
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 1642
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 171763
telemt_user_connections_current{user="hello"} 792
telemt_user_octets_from_client{user="hello"} 1866683388 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 53760077076 (50.07 GB)
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 122
```