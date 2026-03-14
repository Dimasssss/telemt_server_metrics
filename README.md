# Server Metrics 2026-03-14 12:17:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 195551.9 (54h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5669583
telemt_connections_bad_total 59921
telemt_handshake_timeouts_total 124940
telemt_upstream_connect_attempt_total 41032
telemt_upstream_connect_success_total 40769
telemt_upstream_connect_fail_total 263
telemt_upstream_connect_attempts_per_request{bucket="1"} 41032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18535
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 263
telemt_me_keepalive_timeout_total 7845
telemt_me_reconnect_attempts_total 45066
telemt_me_reconnect_success_total 28690
telemt_me_reader_eof_total 30866
telemt_me_idle_close_by_peer_total 30865
telemt_me_route_drop_no_conn_total 2148485
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5201065
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 20066
telemt_desync_full_logged_total 5491
telemt_desync_suppressed_total 14575
telemt_desync_frames_bucket_total{bucket="1_2"} 4850
telemt_desync_frames_bucket_total{bucket="3_10"} 7637
telemt_desync_frames_bucket_total{bucket="gt_10"} 7579
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 29616
telemt_me_refill_failed_total 506
telemt_me_writer_restored_same_endpoint_total 28677
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 926
telemt_user_connections_total{user="hello"} 5202624
telemt_user_connections_current{user="hello"} 1715
telemt_user_octets_from_client{user="hello"} 80692397080 (75.15 GB)
telemt_user_octets_to_client{user="hello"} 1655527094021 (1.51 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 461
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 95215.7 (26h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1096486
telemt_connections_bad_total 58953
telemt_handshake_timeouts_total 25466
telemt_upstream_connect_attempt_total 24531
telemt_upstream_connect_success_total 24227
telemt_upstream_connect_fail_total 304
telemt_upstream_connect_attempts_per_request{bucket="1"} 24531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10728
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 264
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 304
telemt_me_keepalive_timeout_total 2406
telemt_me_reconnect_attempts_total 35183
telemt_me_reconnect_success_total 17461
telemt_me_reader_eof_total 18905
telemt_me_idle_close_by_peer_total 18904
telemt_me_route_drop_no_conn_total 371107
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 904071
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2503
telemt_desync_full_logged_total 786
telemt_desync_suppressed_total 1717
telemt_desync_frames_bucket_total{bucket="1_2"} 647
telemt_desync_frames_bucket_total{bucket="3_10"} 1038
telemt_desync_frames_bucket_total{bucket="gt_10"} 818
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18261
telemt_me_refill_failed_total 547
telemt_me_writer_restored_same_endpoint_total 17453
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 800
telemt_user_connections_total{user="hello"} 905982
telemt_user_connections_current{user="hello"} 616
telemt_user_octets_from_client{user="hello"} 9886317205 (9.21 GB)
telemt_user_octets_to_client{user="hello"} 320465466080 (298.46 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 225172.3 (62h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4023251
telemt_connections_bad_total 46491
telemt_handshake_timeouts_total 275515
telemt_upstream_connect_attempt_total 50700
telemt_upstream_connect_success_total 50679
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 50700
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23680
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 259
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11269
telemt_me_reconnect_attempts_total 45130
telemt_me_reconnect_success_total 39129
telemt_me_reader_eof_total 41566
telemt_me_idle_close_by_peer_total 41564
telemt_me_route_drop_no_conn_total 1382349
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3365202
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10792
telemt_desync_full_logged_total 3645
telemt_desync_suppressed_total 7147
telemt_desync_frames_bucket_total{bucket="1_2"} 1971
telemt_desync_frames_bucket_total{bucket="3_10"} 3900
telemt_desync_frames_bucket_total{bucket="gt_10"} 4921
telemt_pool_swap_total 209
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 39708
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 39088
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 579
telemt_user_connections_total{user="hello"} 3364354
telemt_user_connections_current{user="hello"} 988
telemt_user_octets_from_client{user="hello"} 57505877876 (53.56 GB)
telemt_user_octets_to_client{user="hello"} 1200583918557 (1.09 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 278
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 225174.9 (62h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2627990
telemt_connections_bad_total 23512
telemt_handshake_timeouts_total 339038
telemt_upstream_connect_attempt_total 69481
telemt_upstream_connect_success_total 66972
telemt_upstream_connect_fail_total 2372
telemt_upstream_connect_attempts_per_request{bucket="1"} 69207
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26936
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2371
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20962
telemt_me_reconnect_attempts_total 61498
telemt_me_reconnect_success_total 48715
telemt_me_reader_eof_total 52186
telemt_me_idle_close_by_peer_total 52178
telemt_me_route_drop_no_conn_total 872983
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2054304
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4117
telemt_desync_full_logged_total 1355
telemt_desync_suppressed_total 2762
telemt_desync_frames_bucket_total{bucket="1_2"} 1171
telemt_desync_frames_bucket_total{bucket="3_10"} 1683
telemt_desync_frames_bucket_total{bucket="gt_10"} 1263
telemt_pool_swap_total 193
telemt_me_writer_removed_unexpected_total 49540
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 48690
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 825
telemt_user_connections_total{user="hello"} 2060744
telemt_user_connections_current{user="hello"} 470
telemt_user_octets_from_client{user="hello"} 30483824775 (28.39 GB)
telemt_user_octets_to_client{user="hello"} 733353798110 (682.99 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 94608.5 (26h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1082005
telemt_connections_bad_total 18119
telemt_handshake_timeouts_total 13920
telemt_upstream_connect_attempt_total 22910
telemt_upstream_connect_success_total 22265
telemt_upstream_connect_fail_total 645
telemt_upstream_connect_attempts_per_request{bucket="1"} 22910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11563
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 645
telemt_me_keepalive_timeout_total 1793
telemt_me_reconnect_attempts_total 83952
telemt_me_reconnect_success_total 17538
telemt_me_reader_eof_total 20021
telemt_me_idle_close_by_peer_total 20020
telemt_me_route_drop_no_conn_total 437292
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1002476
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2690
telemt_desync_full_logged_total 842
telemt_desync_suppressed_total 1848
telemt_desync_frames_bucket_total{bucket="1_2"} 972
telemt_desync_frames_bucket_total{bucket="3_10"} 947
telemt_desync_frames_bucket_total{bucket="gt_10"} 771
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19772
telemt_me_refill_failed_total 2070
telemt_me_writer_restored_same_endpoint_total 17533
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2234
telemt_user_connections_total{user="hello"} 1001676
telemt_user_connections_current{user="hello"} 776
telemt_user_octets_from_client{user="hello"} 17305498444 (16.12 GB)
telemt_user_octets_to_client{user="hello"} 337352252236 (314.18 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 91
```