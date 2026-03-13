# Server Metrics 2026-03-13 21:38:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 142766.6 (39h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4488010
telemt_connections_bad_total 38133
telemt_handshake_timeouts_total 106577
telemt_upstream_connect_attempt_total 29838
telemt_upstream_connect_success_total 29632
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 29838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_timeout_total 6620
telemt_me_reconnect_attempts_total 30300
telemt_me_reconnect_success_total 20180
telemt_me_reader_eof_total 21652
telemt_me_idle_close_by_peer_total 21651
telemt_me_route_drop_no_conn_total 1693175
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4111787
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16371
telemt_desync_full_logged_total 4379
telemt_desync_suppressed_total 11992
telemt_desync_frames_bucket_total{bucket="1_2"} 4082
telemt_desync_frames_bucket_total{bucket="3_10"} 6257
telemt_desync_frames_bucket_total{bucket="gt_10"} 6032
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 20786
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 20167
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 606
telemt_user_connections_total{user="hello"} 4113916
telemt_user_connections_current{user="hello"} 935
telemt_user_octets_from_client{user="hello"} 60476714952 (56.32 GB)
telemt_user_octets_to_client{user="hello"} 1303337437737 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 263
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 42430.3 (11h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 575728
telemt_connections_bad_total 41499
telemt_handshake_timeouts_total 12293
telemt_upstream_connect_attempt_total 12052
telemt_upstream_connect_success_total 11827
telemt_upstream_connect_fail_total 224
telemt_upstream_connect_attempts_per_request{bucket="1"} 12051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4735
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 197
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 224
telemt_me_keepalive_timeout_total 1899
telemt_me_reconnect_attempts_total 11072
telemt_me_reconnect_success_total 7646
telemt_me_reader_eof_total 8092
telemt_me_idle_close_by_peer_total 8091
telemt_me_route_drop_no_conn_total 211445
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 499656
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1641
telemt_desync_full_logged_total 443
telemt_desync_suppressed_total 1198
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 711
telemt_desync_frames_bucket_total{bucket="gt_10"} 582
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 7861
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 7638
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 215
telemt_user_connections_total{user="hello"} 501584
telemt_user_connections_current{user="hello"} 395
telemt_user_octets_from_client{user="hello"} 5402679133 (5.03 GB)
telemt_user_octets_to_client{user="hello"} 164623529756 (153.32 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 172386.9 (47h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3265785
telemt_connections_bad_total 31321
telemt_handshake_timeouts_total 219143
telemt_upstream_connect_attempt_total 38268
telemt_upstream_connect_success_total 38247
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 38268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18086
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10260
telemt_me_reconnect_attempts_total 34288
telemt_me_reconnect_success_total 29339
telemt_me_reader_eof_total 31138
telemt_me_idle_close_by_peer_total 31137
telemt_me_route_drop_no_conn_total 1117989
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2709028
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8908
telemt_desync_full_logged_total 2990
telemt_desync_suppressed_total 5918
telemt_desync_frames_bucket_total{bucket="1_2"} 1469
telemt_desync_frames_bucket_total{bucket="3_10"} 3245
telemt_desync_frames_bucket_total{bucket="gt_10"} 4194
telemt_pool_swap_total 159
telemt_me_writer_removed_unexpected_total 29772
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 29298
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 433
telemt_user_connections_total{user="hello"} 2708300
telemt_user_connections_current{user="hello"} 535
telemt_user_octets_from_client{user="hello"} 44371301692 (41.32 GB)
telemt_user_octets_to_client{user="hello"} 955142653677 (889.55 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 172389.6 (47h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2125148
telemt_connections_bad_total 22807
telemt_handshake_timeouts_total 209681
telemt_upstream_connect_attempt_total 53569
telemt_upstream_connect_success_total 51125
telemt_upstream_connect_fail_total 2307
telemt_upstream_connect_attempts_per_request{bucket="1"} 53295
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20330
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2306
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20238
telemt_me_reconnect_attempts_total 44528
telemt_me_reconnect_success_total 35514
telemt_me_reader_eof_total 38114
telemt_me_idle_close_by_peer_total 38107
telemt_me_route_drop_no_conn_total 748202
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1744155
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3770
telemt_desync_full_logged_total 1204
telemt_desync_suppressed_total 2566
telemt_desync_frames_bucket_total{bucket="1_2"} 994
telemt_desync_frames_bucket_total{bucket="3_10"} 1571
telemt_desync_frames_bucket_total{bucket="gt_10"} 1205
telemt_pool_swap_total 151
telemt_me_writer_removed_unexpected_total 36102
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 35490
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 588
telemt_user_connections_total{user="hello"} 1750038
telemt_user_connections_current{user="hello"} 293
telemt_user_octets_from_client{user="hello"} 27036839575 (25.18 GB)
telemt_user_octets_to_client{user="hello"} 654899630014 (609.92 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 41823.0 (11h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 614637
telemt_connections_bad_total 5842
telemt_handshake_timeouts_total 5661
telemt_upstream_connect_attempt_total 9350
telemt_upstream_connect_success_total 9045
telemt_upstream_connect_fail_total 305
telemt_upstream_connect_attempts_per_request{bucket="1"} 9350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4655
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 305
telemt_me_keepalive_timeout_total 976
telemt_me_reconnect_attempts_total 31558
telemt_me_reconnect_success_total 6937
telemt_me_reader_eof_total 7836
telemt_me_idle_close_by_peer_total 7835
telemt_me_route_drop_no_conn_total 233367
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 576178
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1520
telemt_desync_full_logged_total 474
telemt_desync_suppressed_total 1046
telemt_desync_frames_bucket_total{bucket="1_2"} 459
telemt_desync_frames_bucket_total{bucket="3_10"} 602
telemt_desync_frames_bucket_total{bucket="gt_10"} 459
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 7766
telemt_me_refill_failed_total 767
telemt_me_writer_restored_same_endpoint_total 6933
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 829
telemt_user_connections_total{user="hello"} 576090
telemt_user_connections_current{user="hello"} 416
telemt_user_octets_from_client{user="hello"} 8513795236 (7.93 GB)
telemt_user_octets_to_client{user="hello"} 183396885932 (170.80 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 50
```