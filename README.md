# Server Metrics 2026-03-14 11:36:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 193096.6 (53h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5579640
telemt_connections_bad_total 58300
telemt_handshake_timeouts_total 123235
telemt_upstream_connect_attempt_total 40480
telemt_upstream_connect_success_total 40222
telemt_upstream_connect_fail_total 258
telemt_upstream_connect_attempts_per_request{bucket="1"} 40480
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 258
telemt_me_keepalive_timeout_total 7727
telemt_me_reconnect_attempts_total 44650
telemt_me_reconnect_success_total 28279
telemt_me_reader_eof_total 30449
telemt_me_idle_close_by_peer_total 30448
telemt_me_route_drop_no_conn_total 2110677
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5116987
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19637
telemt_desync_full_logged_total 5356
telemt_desync_suppressed_total 14281
telemt_desync_frames_bucket_total{bucket="1_2"} 4770
telemt_desync_frames_bucket_total{bucket="3_10"} 7481
telemt_desync_frames_bucket_total{bucket="gt_10"} 7386
telemt_pool_swap_total 163
telemt_me_writer_removed_unexpected_total 29202
telemt_me_refill_failed_total 506
telemt_me_writer_restored_same_endpoint_total 28266
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 923
telemt_user_connections_total{user="hello"} 5118420
telemt_user_connections_current{user="hello"} 1817
telemt_user_octets_from_client{user="hello"} 79174191024 (73.74 GB)
telemt_user_octets_to_client{user="hello"} 1630336414901 (1.48 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 482
telemt_user_unique_ips_recent_window{user="hello"} 213
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 92760.4 (25h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1060770
telemt_connections_bad_total 58876
telemt_handshake_timeouts_total 24445
telemt_upstream_connect_attempt_total 24208
telemt_upstream_connect_success_total 23910
telemt_upstream_connect_fail_total 298
telemt_upstream_connect_attempts_per_request{bucket="1"} 24208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10576
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 262
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 298
telemt_me_keepalive_timeout_total 2299
telemt_me_reconnect_attempts_total 30919
telemt_me_reconnect_success_total 17263
telemt_me_reader_eof_total 18580
telemt_me_idle_close_by_peer_total 18579
telemt_me_route_drop_no_conn_total 357834
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 870927
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2431
telemt_desync_full_logged_total 761
telemt_desync_suppressed_total 1670
telemt_desync_frames_bucket_total{bucket="1_2"} 611
telemt_desync_frames_bucket_total{bucket="3_10"} 1017
telemt_desync_frames_bucket_total{bucket="gt_10"} 803
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 17935
telemt_me_refill_failed_total 420
telemt_me_writer_restored_same_endpoint_total 17255
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 672
telemt_user_connections_total{user="hello"} 872841
telemt_user_connections_current{user="hello"} 750
telemt_user_octets_from_client{user="hello"} 9520889805 (8.87 GB)
telemt_user_octets_to_client{user="hello"} 307064812452 (285.98 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 222717.2 (61h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3955283
telemt_connections_bad_total 46184
telemt_handshake_timeouts_total 266160
telemt_upstream_connect_attempt_total 50273
telemt_upstream_connect_success_total 50252
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 50273
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23453
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 259
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11100
telemt_me_reconnect_attempts_total 44834
telemt_me_reconnect_success_total 38834
telemt_me_reader_eof_total 41249
telemt_me_idle_close_by_peer_total 41247
telemt_me_route_drop_no_conn_total 1359284
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3308109
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10651
telemt_desync_full_logged_total 3601
telemt_desync_suppressed_total 7050
telemt_desync_frames_bucket_total{bucket="1_2"} 1938
telemt_desync_frames_bucket_total{bucket="3_10"} 3852
telemt_desync_frames_bucket_total{bucket="gt_10"} 4861
telemt_pool_swap_total 206
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 39409
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 38793
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 575
telemt_user_connections_total{user="hello"} 3307255
telemt_user_connections_current{user="hello"} 1029
telemt_user_octets_from_client{user="hello"} 56230730480 (52.37 GB)
telemt_user_octets_to_client{user="hello"} 1184536849909 (1.08 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 222719.6 (61h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2593706
telemt_connections_bad_total 23506
telemt_handshake_timeouts_total 331677
telemt_upstream_connect_attempt_total 68881
telemt_upstream_connect_success_total 66374
telemt_upstream_connect_fail_total 2370
telemt_upstream_connect_attempts_per_request{bucket="1"} 68607
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26676
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2369
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20808
telemt_me_reconnect_attempts_total 61031
telemt_me_reconnect_success_total 48252
telemt_me_reader_eof_total 51703
telemt_me_idle_close_by_peer_total 51695
telemt_me_route_drop_no_conn_total 863023
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2029194
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4096
telemt_desync_full_logged_total 1346
telemt_desync_suppressed_total 2750
telemt_desync_frames_bucket_total{bucket="1_2"} 1163
telemt_desync_frames_bucket_total{bucket="3_10"} 1673
telemt_desync_frames_bucket_total{bucket="gt_10"} 1260
telemt_pool_swap_total 191
telemt_me_writer_removed_unexpected_total 49071
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 48227
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 819
telemt_user_connections_total{user="hello"} 2035556
telemt_user_connections_current{user="hello"} 445
telemt_user_octets_from_client{user="hello"} 30195160487 (28.12 GB)
telemt_user_octets_to_client{user="hello"} 727928731818 (677.94 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 92153.1 (25h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1046282
telemt_connections_bad_total 18080
telemt_handshake_timeouts_total 13674
telemt_upstream_connect_attempt_total 22649
telemt_upstream_connect_success_total 22030
telemt_upstream_connect_fail_total 619
telemt_upstream_connect_attempts_per_request{bucket="1"} 22649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10568
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11436
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 619
telemt_me_keepalive_timeout_total 1747
telemt_me_reconnect_attempts_total 81118
telemt_me_reconnect_success_total 17425
telemt_me_reader_eof_total 19822
telemt_me_idle_close_by_peer_total 19821
telemt_me_route_drop_no_conn_total 423406
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 968157
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2607
telemt_desync_full_logged_total 814
telemt_desync_suppressed_total 1793
telemt_desync_frames_bucket_total{bucket="1_2"} 919
telemt_desync_frames_bucket_total{bucket="3_10"} 938
telemt_desync_frames_bucket_total{bucket="gt_10"} 750
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19573
telemt_me_refill_failed_total 1985
telemt_me_writer_restored_same_endpoint_total 17420
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2148
telemt_user_connections_total{user="hello"} 967372
telemt_user_connections_current{user="hello"} 669
telemt_user_octets_from_client{user="hello"} 16966879800 (15.80 GB)
telemt_user_octets_to_client{user="hello"} 327455441308 (304.97 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 88
```