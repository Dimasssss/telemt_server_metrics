# Server Metrics 2026-03-11 18:56:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 102571.5 (28h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2603141
telemt_connections_bad_total 48563
telemt_handshake_timeouts_total 57015
telemt_upstream_connect_attempt_total 21572
telemt_upstream_connect_success_total 21560
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 21572
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10555
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5317
telemt_me_reconnect_attempts_total 34269
telemt_me_reconnect_success_total 16387
telemt_me_reader_eof_total 17724
telemt_me_idle_close_by_peer_total 17724
telemt_me_route_drop_no_conn_total 980467
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2380912
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12038
telemt_desync_full_logged_total 3330
telemt_desync_suppressed_total 8708
telemt_desync_frames_bucket_total{bucket="1_2"} 2957
telemt_desync_frames_bucket_total{bucket="3_10"} 4636
telemt_desync_frames_bucket_total{bucket="gt_10"} 4445
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 17129
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 16381
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 742
telemt_user_connections_total{user="hello"} 2379262
telemt_user_connections_current{user="hello"} 1227
telemt_user_octets_from_client{user="hello"} 35537069632 (33.10 GB)
telemt_user_octets_to_client{user="hello"} 675250422968 (628.88 GB)
telemt_user_unique_ips_current{user="hello"} 335
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 102628.3 (28h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 972872
telemt_connections_bad_total 16425
telemt_handshake_timeouts_total 86956
telemt_upstream_connect_attempt_total 31789
telemt_upstream_connect_success_total 28820
telemt_upstream_connect_fail_total 2969
telemt_upstream_connect_attempts_per_request{bucket="1"} 31789
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12961
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2046
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2969
telemt_me_keepalive_timeout_total 2831
telemt_me_reconnect_attempts_total 22835
telemt_me_reconnect_success_total 20723
telemt_me_reader_eof_total 21923
telemt_me_idle_close_by_peer_total 21920
telemt_me_route_drop_no_conn_total 367396
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 811525
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3214
telemt_desync_full_logged_total 1042
telemt_desync_suppressed_total 2172
telemt_desync_frames_bucket_total{bucket="1_2"} 1014
telemt_desync_frames_bucket_total{bucket="3_10"} 1146
telemt_desync_frames_bucket_total{bucket="gt_10"} 1054
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 21011
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 20700
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 288
telemt_user_connections_total{user="hello"} 813976
telemt_user_connections_current{user="hello"} 402
telemt_user_octets_from_client{user="hello"} 9788510218 (9.12 GB)
telemt_user_octets_to_client{user="hello"} 235026773160 (218.89 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 102628.2 (28h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1673072
telemt_connections_bad_total 10482
telemt_handshake_timeouts_total 133330
telemt_upstream_connect_attempt_total 26599
telemt_upstream_connect_success_total 26267
telemt_upstream_connect_fail_total 332
telemt_upstream_connect_attempts_per_request{bucket="1"} 26599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11974
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 332
telemt_me_keepalive_timeout_total 1972
telemt_me_reconnect_attempts_total 48363
telemt_me_reconnect_success_total 20020
telemt_me_reader_eof_total 21764
telemt_me_idle_close_by_peer_total 21764
telemt_me_route_drop_no_conn_total 609471
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1465739
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4073
telemt_desync_full_logged_total 1193
telemt_desync_suppressed_total 2880
telemt_desync_frames_bucket_total{bucket="1_2"} 946
telemt_desync_frames_bucket_total{bucket="3_10"} 1545
telemt_desync_frames_bucket_total{bucket="gt_10"} 1582
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 21184
telemt_me_refill_failed_total 880
telemt_me_writer_restored_same_endpoint_total 20008
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1164
telemt_user_connections_total{user="hello"} 1465407
telemt_user_connections_current{user="hello"} 662
telemt_user_octets_from_client{user="hello"} 19005138493 (17.70 GB)
telemt_user_octets_to_client{user="hello"} 445856172889 (415.24 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 102628.8 (28h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1194373
telemt_connections_bad_total 78200
telemt_handshake_timeouts_total 110368
telemt_upstream_connect_attempt_total 27619
telemt_upstream_connect_success_total 27619
telemt_upstream_connect_attempts_per_request{bucket="1"} 27619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12552
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1418
telemt_me_reconnect_attempts_total 27108
telemt_me_reconnect_success_total 22497
telemt_me_reader_eof_total 23886
telemt_me_idle_close_by_peer_total 23885
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 398673
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 971074
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2034
telemt_desync_full_logged_total 778
telemt_desync_suppressed_total 1256
telemt_desync_frames_bucket_total{bucket="1_2"} 738
telemt_desync_frames_bucket_total{bucket="3_10"} 701
telemt_desync_frames_bucket_total{bucket="gt_10"} 595
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 22879
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 22464
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 382
telemt_user_connections_total{user="hello"} 970335
telemt_user_connections_current{user="hello"} 552
telemt_user_octets_from_client{user="hello"} 11482837068 (10.69 GB)
telemt_user_octets_to_client{user="hello"} 294786242752 (274.54 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 7304.8 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119050
telemt_connections_bad_total 627
telemt_handshake_timeouts_total 710
telemt_upstream_connect_attempt_total 2025
telemt_upstream_connect_success_total 2024
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 931
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 1608
telemt_me_reconnect_success_total 1591
telemt_me_reader_eof_total 1621
telemt_me_idle_close_by_peer_total 1621
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 40863
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109679
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 222
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 150
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1609
telemt_me_writer_restored_same_endpoint_total 1567
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 109650
telemt_user_connections_current{user="hello"} 627
telemt_user_octets_from_client{user="hello"} 6464562092 (6.02 GB)
telemt_user_octets_to_client{user="hello"} 36800093232 (34.27 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 99
```