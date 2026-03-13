# Server Metrics 2026-03-13 14:14:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 116138.5 (32h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3540533
telemt_connections_bad_total 37397
telemt_handshake_timeouts_total 60388
telemt_upstream_connect_attempt_total 22701
telemt_upstream_connect_success_total 22575
telemt_upstream_connect_fail_total 126
telemt_upstream_connect_attempts_per_request{bucket="1"} 22701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10870
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 126
telemt_me_keepalive_timeout_total 2150
telemt_me_reconnect_attempts_total 26895
telemt_me_reconnect_success_total 16810
telemt_me_reader_eof_total 18070
telemt_me_idle_close_by_peer_total 18069
telemt_me_route_drop_no_conn_total 1316566
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3251508
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13444
telemt_desync_full_logged_total 3521
telemt_desync_suppressed_total 9923
telemt_desync_frames_bucket_total{bucket="1_2"} 3422
telemt_desync_frames_bucket_total{bucket="3_10"} 5083
telemt_desync_frames_bucket_total{bucket="gt_10"} 4939
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 17360
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16797
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 550
telemt_user_connections_total{user="hello"} 3251219
telemt_user_connections_current{user="hello"} 1841
telemt_user_octets_from_client{user="hello"} 44783419964 (41.71 GB)
telemt_user_octets_to_client{user="hello"} 1033821891872 (962.82 GB)
telemt_user_unique_ips_current{user="hello"} 458
telemt_user_unique_ips_recent_window{user="hello"} 270
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 15802.2 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221431
telemt_connections_bad_total 12580
telemt_handshake_timeouts_total 5571
telemt_upstream_connect_attempt_total 3930
telemt_upstream_connect_success_total 3852
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 3930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1846
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 5300
telemt_me_reconnect_success_total 3012
telemt_me_reader_eof_total 3181
telemt_me_idle_close_by_peer_total 3181
telemt_me_route_drop_no_conn_total 80412
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 197489
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 751
telemt_desync_full_logged_total 181
telemt_desync_suppressed_total 570
telemt_desync_frames_bucket_total{bucket="1_2"} 138
telemt_desync_frames_bucket_total{bucket="3_10"} 380
telemt_desync_frames_bucket_total{bucket="gt_10"} 233
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3112
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 3005
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 197516
telemt_user_connections_current{user="hello"} 603
telemt_user_octets_from_client{user="hello"} 2063197220 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 56888918540 (52.98 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 145758.9 (40h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2652822
telemt_connections_bad_total 27307
telemt_handshake_timeouts_total 177935
telemt_upstream_connect_attempt_total 32861
telemt_upstream_connect_success_total 32851
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 32861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15640
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3238
telemt_me_reconnect_attempts_total 27821
telemt_me_reconnect_success_total 25275
telemt_me_reader_eof_total 26799
telemt_me_idle_close_by_peer_total 26798
telemt_me_route_drop_no_conn_total 891809
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2165993
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7685
telemt_desync_full_logged_total 2504
telemt_desync_suppressed_total 5181
telemt_desync_frames_bucket_total{bucket="1_2"} 1203
telemt_desync_frames_bucket_total{bucket="3_10"} 2797
telemt_desync_frames_bucket_total{bucket="gt_10"} 3685
telemt_pool_swap_total 136
telemt_me_writer_removed_unexpected_total 25571
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 25234
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 296
telemt_user_connections_total{user="hello"} 2165379
telemt_user_connections_current{user="hello"} 1012
telemt_user_octets_from_client{user="hello"} 36268244068 (33.78 GB)
telemt_user_octets_to_client{user="hello"} 769345088797 (716.51 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 297
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 145759.3 (40h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1691371
telemt_connections_bad_total 18058
telemt_handshake_timeouts_total 122407
telemt_upstream_connect_attempt_total 46286
telemt_upstream_connect_success_total 43964
telemt_upstream_connect_fail_total 2185
telemt_upstream_connect_attempts_per_request{bucket="1"} 46012
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26482
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17391
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2184
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11845
telemt_me_reconnect_attempts_total 39841
telemt_me_reconnect_success_total 30873
telemt_me_reader_eof_total 33191
telemt_me_idle_close_by_peer_total 33184
telemt_me_route_drop_no_conn_total 603703
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1414162
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2818
telemt_desync_full_logged_total 916
telemt_desync_suppressed_total 1902
telemt_desync_frames_bucket_total{bucket="1_2"} 753
telemt_desync_frames_bucket_total{bucket="3_10"} 1172
telemt_desync_frames_bucket_total{bucket="gt_10"} 893
telemt_pool_swap_total 127
telemt_me_writer_removed_unexpected_total 31383
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 30849
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 1418878
telemt_user_connections_current{user="hello"} 723
telemt_user_octets_from_client{user="hello"} 21906900465 (20.40 GB)
telemt_user_octets_to_client{user="hello"} 548090814374 (510.45 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 15194.9 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239740
telemt_connections_bad_total 3868
telemt_handshake_timeouts_total 2222
telemt_upstream_connect_attempt_total 3111
telemt_upstream_connect_success_total 3007
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 3111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1564
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 54
telemt_me_reconnect_attempts_total 10300
telemt_me_reconnect_success_total 2224
telemt_me_reader_eof_total 2503
telemt_me_idle_close_by_peer_total 2503
telemt_me_route_drop_no_conn_total 93873
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 224014
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 767
telemt_desync_full_logged_total 245
telemt_desync_suppressed_total 522
telemt_desync_frames_bucket_total{bucket="1_2"} 293
telemt_desync_frames_bucket_total{bucket="3_10"} 301
telemt_desync_frames_bucket_total{bucket="gt_10"} 173
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2480
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 2220
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 256
telemt_user_connections_total{user="hello"} 223996
telemt_user_connections_current{user="hello"} 761
telemt_user_octets_from_client{user="hello"} 2489344132 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 72205771220 (67.25 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 106
```