# Server Metrics 2026-03-14 10:25:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 188801.6 (52h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5415893
telemt_connections_bad_total 56076
telemt_handshake_timeouts_total 120115
telemt_upstream_connect_attempt_total 39675
telemt_upstream_connect_success_total 39419
telemt_upstream_connect_fail_total 256
telemt_upstream_connect_attempts_per_request{bucket="1"} 39675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17904
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 256
telemt_me_keepalive_timeout_total 7600
telemt_me_reconnect_attempts_total 40170
telemt_me_reconnect_success_total 27704
telemt_me_reader_eof_total 29733
telemt_me_idle_close_by_peer_total 29732
telemt_me_route_drop_no_conn_total 2047142
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4962165
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18924
telemt_desync_full_logged_total 5180
telemt_desync_suppressed_total 13744
telemt_desync_frames_bucket_total{bucket="1_2"} 4650
telemt_desync_frames_bucket_total{bucket="3_10"} 7208
telemt_desync_frames_bucket_total{bucket="gt_10"} 7066
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 28498
telemt_me_refill_failed_total 384
telemt_me_writer_restored_same_endpoint_total 27691
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 794
telemt_user_connections_total{user="hello"} 4963616
telemt_user_connections_current{user="hello"} 1588
telemt_user_octets_from_client{user="hello"} 76034434040 (70.81 GB)
telemt_user_octets_to_client{user="hello"} 1580318381969 (1.44 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 466
telemt_user_unique_ips_recent_window{user="hello"} 223
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 88465.5 (24h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 998683
telemt_connections_bad_total 57381
telemt_handshake_timeouts_total 21622
telemt_upstream_connect_attempt_total 23224
telemt_upstream_connect_success_total 22932
telemt_upstream_connect_fail_total 292
telemt_upstream_connect_attempts_per_request{bucket="1"} 23224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10174
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 43
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 292
telemt_me_keepalive_timeout_total 2260
telemt_me_reconnect_attempts_total 26360
telemt_me_reconnect_success_total 16484
telemt_me_reader_eof_total 17674
telemt_me_idle_close_by_peer_total 17673
telemt_me_route_drop_no_conn_total 335386
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 815455
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2291
telemt_desync_full_logged_total 717
telemt_desync_suppressed_total 1574
telemt_desync_frames_bucket_total{bucket="1_2"} 540
telemt_desync_frames_bucket_total{bucket="3_10"} 972
telemt_desync_frames_bucket_total{bucket="gt_10"} 779
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 17028
telemt_me_refill_failed_total 302
telemt_me_writer_restored_same_endpoint_total 16476
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 544
telemt_user_connections_total{user="hello"} 817350
telemt_user_connections_current{user="hello"} 669
telemt_user_octets_from_client{user="hello"} 8871664205 (8.26 GB)
telemt_user_octets_to_client{user="hello"} 286201496048 (266.55 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 218422.2 (60h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3850341
telemt_connections_bad_total 45735
telemt_handshake_timeouts_total 254586
telemt_upstream_connect_attempt_total 49326
telemt_upstream_connect_success_total 49305
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 49326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26046
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23001
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 251
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11021
telemt_me_reconnect_attempts_total 43120
telemt_me_reconnect_success_total 38120
telemt_me_reader_eof_total 40461
telemt_me_idle_close_by_peer_total 40460
telemt_me_route_drop_no_conn_total 1321786
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3217910
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10325
telemt_desync_full_logged_total 3511
telemt_desync_suppressed_total 6814
telemt_desync_frames_bucket_total{bucket="1_2"} 1870
telemt_desync_frames_bucket_total{bucket="3_10"} 3738
telemt_desync_frames_bucket_total{bucket="gt_10"} 4717
telemt_pool_swap_total 203
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 38652
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 38079
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 532
telemt_user_connections_total{user="hello"} 3217050
telemt_user_connections_current{user="hello"} 907
telemt_user_octets_from_client{user="hello"} 54506317880 (50.76 GB)
telemt_user_octets_to_client{user="hello"} 1153736244205 (1.05 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 218424.7 (60h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2538956
telemt_connections_bad_total 23420
telemt_handshake_timeouts_total 321502
telemt_upstream_connect_attempt_total 67651
telemt_upstream_connect_success_total 65146
telemt_upstream_connect_fail_total 2368
telemt_upstream_connect_attempts_per_request{bucket="1"} 67377
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26098
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2367
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20746
telemt_me_reconnect_attempts_total 58912
telemt_me_reconnect_success_total 47256
telemt_me_reader_eof_total 50640
telemt_me_idle_close_by_peer_total 50632
telemt_me_route_drop_no_conn_total 846616
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1987738
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4048
telemt_desync_full_logged_total 1324
telemt_desync_suppressed_total 2724
telemt_desync_frames_bucket_total{bucket="1_2"} 1142
telemt_desync_frames_bucket_total{bucket="3_10"} 1654
telemt_desync_frames_bucket_total{bucket="gt_10"} 1252
telemt_pool_swap_total 189
telemt_me_writer_removed_unexpected_total 48030
telemt_me_refill_failed_total 355
telemt_me_writer_restored_same_endpoint_total 47232
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 774
telemt_user_connections_total{user="hello"} 1993945
telemt_user_connections_current{user="hello"} 474
telemt_user_octets_from_client{user="hello"} 29735733931 (27.69 GB)
telemt_user_octets_to_client{user="hello"} 718452423362 (669.11 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 87858.2 (24h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 985015
telemt_connections_bad_total 16286
telemt_handshake_timeouts_total 12944
telemt_upstream_connect_attempt_total 22064
telemt_upstream_connect_success_total 21472
telemt_upstream_connect_fail_total 592
telemt_upstream_connect_attempts_per_request{bucket="1"} 22064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11192
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 592
telemt_me_keepalive_timeout_total 1696
telemt_me_reconnect_attempts_total 73904
telemt_me_reconnect_success_total 17091
telemt_me_reader_eof_total 19277
telemt_me_idle_close_by_peer_total 19276
telemt_me_route_drop_no_conn_total 381724
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 911938
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2449
telemt_desync_full_logged_total 763
telemt_desync_suppressed_total 1686
telemt_desync_frames_bucket_total{bucket="1_2"} 829
telemt_desync_frames_bucket_total{bucket="3_10"} 907
telemt_desync_frames_bucket_total{bucket="gt_10"} 713
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19024
telemt_me_refill_failed_total 1770
telemt_me_writer_restored_same_endpoint_total 17086
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1933
telemt_user_connections_total{user="hello"} 911879
telemt_user_connections_current{user="hello"} 707
telemt_user_octets_from_client{user="hello"} 16195144236 (15.08 GB)
telemt_user_octets_to_client{user="hello"} 306060611664 (285.04 GB)
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 104
```