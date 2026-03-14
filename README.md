# Server Metrics 2026-03-14 03:41:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 164544.0 (45h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4720618
telemt_connections_bad_total 39890
telemt_handshake_timeouts_total 109145
telemt_upstream_connect_attempt_total 34771
telemt_upstream_connect_success_total 34541
telemt_upstream_connect_fail_total 230
telemt_upstream_connect_attempts_per_request{bucket="1"} 34771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15565
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 230
telemt_me_keepalive_timeout_total 6737
telemt_me_reconnect_attempts_total 34166
telemt_me_reconnect_success_total 24024
telemt_me_reader_eof_total 25760
telemt_me_idle_close_by_peer_total 25759
telemt_me_route_drop_no_conn_total 1792125
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4329699
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16784
telemt_desync_full_logged_total 4529
telemt_desync_suppressed_total 12255
telemt_desync_frames_bucket_total{bucket="1_2"} 4194
telemt_desync_frames_bucket_total{bucket="3_10"} 6402
telemt_desync_frames_bucket_total{bucket="gt_10"} 6188
telemt_pool_swap_total 142
telemt_me_writer_removed_unexpected_total 24683
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 24011
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 659
telemt_user_connections_total{user="hello"} 4331276
telemt_user_connections_current{user="hello"} 757
telemt_user_octets_from_client{user="hello"} 63329080872 (58.98 GB)
telemt_user_octets_to_client{user="hello"} 1366027763789 (1.24 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 64207.7 (17h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 715126
telemt_connections_bad_total 51936
telemt_handshake_timeouts_total 13287
telemt_upstream_connect_attempt_total 17845
telemt_upstream_connect_success_total 17587
telemt_upstream_connect_fail_total 257
telemt_upstream_connect_attempts_per_request{bucket="1"} 17844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7571
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 218
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 257
telemt_me_keepalive_timeout_total 2095
telemt_me_reconnect_attempts_total 15793
telemt_me_reconnect_success_total 12343
telemt_me_reader_eof_total 13108
telemt_me_idle_close_by_peer_total 13107
telemt_me_route_drop_no_conn_total 239425
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 573048
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1706
telemt_desync_full_logged_total 482
telemt_desync_suppressed_total 1224
telemt_desync_frames_bucket_total{bucket="1_2"} 362
telemt_desync_frames_bucket_total{bucket="3_10"} 750
telemt_desync_frames_bucket_total{bucket="gt_10"} 594
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 12619
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 12335
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 276
telemt_user_connections_total{user="hello"} 575003
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 6129232745 (5.71 GB)
telemt_user_octets_to_client{user="hello"} 191433633400 (178.29 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 194164.6 (53h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3404669
telemt_connections_bad_total 35710
telemt_handshake_timeouts_total 223913
telemt_upstream_connect_attempt_total 43852
telemt_upstream_connect_success_total 43831
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 43852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20529
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10432
telemt_me_reconnect_attempts_total 38832
telemt_me_reconnect_success_total 33866
telemt_me_reader_eof_total 35974
telemt_me_idle_close_by_peer_total 35973
telemt_me_route_drop_no_conn_total 1165187
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2836072
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9375
telemt_desync_full_logged_total 3136
telemt_desync_suppressed_total 6239
telemt_desync_frames_bucket_total{bucket="1_2"} 1615
telemt_desync_frames_bucket_total{bucket="3_10"} 3389
telemt_desync_frames_bucket_total{bucket="gt_10"} 4371
telemt_pool_swap_total 183
telemt_me_writer_removed_unexpected_total 34339
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 33825
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 473
telemt_user_connections_total{user="hello"} 2835293
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 45417916792 (42.30 GB)
telemt_user_octets_to_client{user="hello"} 1014797792673 (945.10 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 194167.1 (53h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2280642
telemt_connections_bad_total 23008
telemt_handshake_timeouts_total 252119
telemt_upstream_connect_attempt_total 60853
telemt_upstream_connect_success_total 58384
telemt_upstream_connect_fail_total 2332
telemt_upstream_connect_attempts_per_request{bucket="1"} 60579
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23310
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2331
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20444
telemt_me_reconnect_attempts_total 50742
telemt_me_reconnect_success_total 41707
telemt_me_reader_eof_total 44731
telemt_me_idle_close_by_peer_total 44724
telemt_me_route_drop_no_conn_total 776356
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1813506
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3832
telemt_desync_full_logged_total 1232
telemt_desync_suppressed_total 2600
telemt_desync_frames_bucket_total{bucket="1_2"} 1022
telemt_desync_frames_bucket_total{bucket="3_10"} 1594
telemt_desync_frames_bucket_total{bucket="gt_10"} 1216
telemt_pool_swap_total 171
telemt_me_writer_removed_unexpected_total 42344
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 41683
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 637
telemt_user_connections_total{user="hello"} 1819443
telemt_user_connections_current{user="hello"} 266
telemt_user_octets_from_client{user="hello"} 27670935803 (25.77 GB)
telemt_user_octets_to_client{user="hello"} 670885620298 (624.81 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 63600.5 (17h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 714269
telemt_connections_bad_total 7954
telemt_handshake_timeouts_total 8704
telemt_upstream_connect_attempt_total 16538
telemt_upstream_connect_success_total 16094
telemt_upstream_connect_fail_total 444
telemt_upstream_connect_attempts_per_request{bucket="1"} 16538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8395
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 444
telemt_me_keepalive_timeout_total 1523
telemt_me_reconnect_attempts_total 50298
telemt_me_reconnect_success_total 12918
telemt_me_reader_eof_total 14397
telemt_me_idle_close_by_peer_total 14396
telemt_me_route_drop_no_conn_total 272021
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 665966
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1705
telemt_desync_full_logged_total 535
telemt_desync_suppressed_total 1170
telemt_desync_frames_bucket_total{bucket="1_2"} 512
telemt_desync_frames_bucket_total{bucket="3_10"} 662
telemt_desync_frames_bucket_total{bucket="gt_10"} 531
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 14195
telemt_me_refill_failed_total 1164
telemt_me_writer_restored_same_endpoint_total 12913
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1277
telemt_user_connections_total{user="hello"} 665844
telemt_user_connections_current{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 12154790640 (11.32 GB)
telemt_user_octets_to_client{user="hello"} 215884791024 (201.06 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 36
```