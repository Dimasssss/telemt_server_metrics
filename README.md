# Server Metrics 2026-03-14 01:38:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 157183.2 (43h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4639770
telemt_connections_bad_total 39797
telemt_handshake_timeouts_total 108171
telemt_upstream_connect_attempt_total 33219
telemt_upstream_connect_success_total 32998
telemt_upstream_connect_fail_total 221
telemt_upstream_connect_attempts_per_request{bucket="1"} 33219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14827
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 221
telemt_me_keepalive_timeout_total 6704
telemt_me_reconnect_attempts_total 32969
telemt_me_reconnect_success_total 22832
telemt_me_reader_eof_total 24486
telemt_me_idle_close_by_peer_total 24485
telemt_me_route_drop_no_conn_total 1756600
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4253301
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16707
telemt_desync_full_logged_total 4504
telemt_desync_suppressed_total 12203
telemt_desync_frames_bucket_total{bucket="1_2"} 4173
telemt_desync_frames_bucket_total{bucket="3_10"} 6379
telemt_desync_frames_bucket_total{bucket="gt_10"} 6155
telemt_pool_swap_total 134
telemt_me_writer_removed_unexpected_total 23478
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 22819
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 646
telemt_user_connections_total{user="hello"} 4255158
telemt_user_connections_current{user="hello"} 525
telemt_user_octets_from_client{user="hello"} 62651249412 (58.35 GB)
telemt_user_octets_to_client{user="hello"} 1344397565709 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 56846.9 (15h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 681970
telemt_connections_bad_total 50958
telemt_handshake_timeouts_total 13001
telemt_upstream_connect_attempt_total 15862
telemt_upstream_connect_success_total 15612
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 15861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6626
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_keepalive_timeout_total 2053
telemt_me_reconnect_attempts_total 14165
telemt_me_reconnect_success_total 10721
telemt_me_reader_eof_total 11376
telemt_me_idle_close_by_peer_total 11375
telemt_me_route_drop_no_conn_total 230532
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 548999
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1651
telemt_desync_full_logged_total 449
telemt_desync_suppressed_total 1202
telemt_desync_frames_bucket_total{bucket="1_2"} 351
telemt_desync_frames_bucket_total{bucket="3_10"} 717
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 10979
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 10713
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 258
telemt_user_connections_total{user="hello"} 550950
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 5931867417 (5.52 GB)
telemt_user_octets_to_client{user="hello"} 177825422644 (165.61 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 186803.7 (51h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3357919
telemt_connections_bad_total 34430
telemt_handshake_timeouts_total 223004
telemt_upstream_connect_attempt_total 41993
telemt_upstream_connect_success_total 41972
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 41993
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19713
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10407
telemt_me_reconnect_attempts_total 37317
telemt_me_reconnect_success_total 32358
telemt_me_reader_eof_total 34354
telemt_me_idle_close_by_peer_total 34353
telemt_me_route_drop_no_conn_total 1151713
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2792616
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9203
telemt_desync_full_logged_total 3087
telemt_desync_suppressed_total 6116
telemt_desync_frames_bucket_total{bucket="1_2"} 1561
telemt_desync_frames_bucket_total{bucket="3_10"} 3333
telemt_desync_frames_bucket_total{bucket="gt_10"} 4309
telemt_pool_swap_total 175
telemt_me_writer_removed_unexpected_total 32813
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 32317
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 455
telemt_user_connections_total{user="hello"} 2791854
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 45011705660 (41.92 GB)
telemt_user_octets_to_client{user="hello"} 995632186877 (927.25 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 186806.1 (51h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2237539
telemt_connections_bad_total 22936
telemt_handshake_timeouts_total 242432
telemt_upstream_connect_attempt_total 58373
telemt_upstream_connect_success_total 55914
telemt_upstream_connect_fail_total 2322
telemt_upstream_connect_attempts_per_request{bucket="1"} 58099
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33458
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22290
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2321
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20401
telemt_me_reconnect_attempts_total 48621
telemt_me_reconnect_success_total 39592
telemt_me_reader_eof_total 42446
telemt_me_idle_close_by_peer_total 42439
telemt_me_route_drop_no_conn_total 768613
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1791121
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3806
telemt_desync_full_logged_total 1223
telemt_desync_suppressed_total 2583
telemt_desync_frames_bucket_total{bucket="1_2"} 1012
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 163
telemt_me_writer_removed_unexpected_total 40217
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 39568
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 625
telemt_user_connections_total{user="hello"} 1797038
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 27436082619 (25.55 GB)
telemt_user_octets_to_client{user="hello"} 664696449242 (619.05 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 56239.7 (15h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 686653
telemt_connections_bad_total 7890
telemt_handshake_timeouts_total 8636
telemt_upstream_connect_attempt_total 14071
telemt_upstream_connect_success_total 13676
telemt_upstream_connect_fail_total 395
telemt_upstream_connect_attempts_per_request{bucket="1"} 14071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7059
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 395
telemt_me_keepalive_timeout_total 1488
telemt_me_reconnect_attempts_total 43012
telemt_me_reconnect_success_total 10853
telemt_me_reader_eof_total 12115
telemt_me_idle_close_by_peer_total 12114
telemt_me_route_drop_no_conn_total 260216
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 639018
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1640
telemt_desync_full_logged_total 514
telemt_desync_suppressed_total 1126
telemt_desync_frames_bucket_total{bucket="1_2"} 493
telemt_desync_frames_bucket_total{bucket="3_10"} 642
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 11952
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 10848
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1099
telemt_user_connections_total{user="hello"} 638911
telemt_user_connections_current{user="hello"} 232
telemt_user_octets_from_client{user="hello"} 10581912956 (9.86 GB)
telemt_user_octets_to_client{user="hello"} 208796559140 (194.46 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 27
```